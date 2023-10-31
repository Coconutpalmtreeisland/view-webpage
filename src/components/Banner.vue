<template>
    <section id="bannerType" class="banner__wrap" :class="element">
        <h2 class="blind">배너 영역</h2>
        <div class="banner__inner">
            <h3 class="title">{{ title }}</h3>
            <p class="desc">
                더 다양한 포트폴리오는 사이트를 통해 제공하고 있습니다.
                <a href="/" title="유튜브 페이지 이동">incredorable12.dothome.co.kr</a>
            </p>
            <span class="small">배너 유형01</span>
        </div>
    </section>
</template>
<script>
export default {
    props: {
        element: String,
        title: String
    }
}
</script>