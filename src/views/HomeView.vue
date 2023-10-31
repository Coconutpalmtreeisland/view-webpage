<script setup>
import Header from "@/components/Header.vue"
import Slider from "@/components/Slider.vue"
import Image from "@/components/Image.vue"
import ImgText from "@/components/ImgText.vue"
import Card from "@/components/Card.vue"
import Banner from "@/components/Banner.vue"
import Text from "@/components/Text.vue"
import Footer from "@/components/Footer.vue"
</script>

<template>
  <Header element="nexon" />
  <main>
    <Slider element="nexon" title="PALMTREE ISLAND" />
    <Image element="nexon section" title="이미지 유형" />
    <ImgText element="nexon section" title="김준수 뮤지컬 작품 살펴보기" />
    <Card element="nexon section" title="김준수의 콘서트" />
    <Banner element="nexon" title="개발자 코코넛" />
    <Text element="nexon section" title="텍스트 유형01" />
  </main>
  <Footer element="nexon section gray" />
</template>
