<template>
    <section id="sliderType" class="slider__wrap" :class="element">
        <h2 class="blind">슬라이드 유형</h2>
        <div class="slider__inner">
            <div class="slider">
                <div class="slider__img">
                    <div class="desc">
                        <span>The Space We Deserve</span>
                        <h3>{{ title }}</h3>
                        <p>
                            꿈꾸는 사람이 마땅히 있어야 할 곳<br />
                            꿈꾸며 만들어 나가는 과정이 빛나는 결실을 맺는 그날까지 멈추지 않고 계속해서 나아가겠습니다.
                        </p>
                        <div class="btn">
                            <a href="/">자세히 보기</a>
                            <a href="/" class="black">사이트 보기</a>
                        </div>
                    </div>
                </div>
                <div class="slider__arrow">
                    <a href="/" class="left"><span class="ir">이전 이미지</span></a>
                    <a href="/" class="right"><span class="ir">다음 이미지</span></a>
                </div>
                <div class="slider__dot">
                    <a href="/" class="dot active"><span class="ir">1</span></a>
                    <a href="/" class="dot"><span class="ir">2</span></a>
                    <a href="/" class="dot"><span class="ir">3</span></a>
                    <a href="/" class="play"><span class="ir">플레이</span></a>
                    <a href="/" class="stop"><span class="ir">정지</span></a>
                </div>
            </div>
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