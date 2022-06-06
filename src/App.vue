<template>
  <div id="app">
    <div>
      <NavbarMenu />
      <ImageAndInfo
        heroHeading="Find a gift for your wife or girlfriend"
        heroText="Struggling to find a gift for your wife or girlfriend? No problem!"
        heroBtnText="find gift now"
        imgSrc="hero-img.png"
        textBoxOrder="0"
        imgBoxOrder="1"
      />
      <ImageAndInfo
        heroHeading="How we work"
        heroText="We've actually already asked hundreds of women what they want, and made a database with the results. All you have to do is take our short survey that only takes seconds, and our proprietary algorithm will match you with a few perfect gift options."
        heroBtnText="Learn More"
        imgSrc="hero-img2.png"
        textBoxOrder="1"
        imgBoxOrder="0"
      />
      <GiftsForAllOccasions />
      <TheBigOrangeSection />
      <OurBestBlogsEver imgSrc="another-silly-couple-image.png" />
      <FooterComponent />
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import NavbarMenu from "./components/NavbarMenu.vue";
import ImageAndInfo from "./components/ImageAndInfo.vue";
import GiftsForAllOccasions from "./components/GiftsForAllOccasions.vue";
import TheBigOrangeSection from "./components/TheBigOrangeSection.vue";
import OurBestBlogsEver from "./components/OurBestBlogsEver.vue";
import FooterComponent from "./components/FooterComponent.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    NavbarMenu,
    ImageAndInfo,
    GiftsForAllOccasions,
    TheBigOrangeSection,
    OurBestBlogsEver,
    FooterComponent,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Khula:wght@300;400;600;700&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Khula", sans-serif;
}
</style>
