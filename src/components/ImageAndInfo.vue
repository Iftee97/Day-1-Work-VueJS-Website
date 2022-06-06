<template>
  <div class="specific-component-container">
    <div class="text-box text-left" :style="{ order: textBoxOrder }">
      <h1 class="hero-heading">{{ heroHeading }}</h1>
      <p class="hero-text">{{ heroText }}</p>
      <button class="hero-btn">{{ heroBtnText }}</button>
    </div>

    <div class="image-box" :style="{ order: imgBoxOrder }">
      <img
        :src="require(`@/assets/${imgSrc}`)"
        alt="hero-img"
        class="hero-img"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "ImageAndInfo",
  props: {
    heroHeading: String,
    heroText: String,
    heroBtnText: String,
    imgSrc: String,
    textBoxOrder: Number,
    imgBoxOrder: Number,
  },
};
</script>

<style scoped>
.specific-component-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  place-content: center;
}

.text-box {
  background-color: #f1f1f2;
  padding: 25%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  /* align-items: center; */
}

.hero-heading {
  font-size: 56px;
  line-height: 69px;
  margin-bottom: 36px;
}

.hero-text {
  font-size: 20px;
  line-height: 140.62%;
  margin-bottom: 52px;
}

.hero-img {
  width: 100%;
  height: 100%;
}

.hero-btn {
  background: #f7941e;
  border: none;
  border-radius: 5px;
  color: #fff;
  font-size: 18px;
  line-height: 22px;
  padding: 16px 32px;
  font-weight: 300;
  text-transform: uppercase;
  width: 50%;
}

.hero-btn:hover {
  color: #000;
  background-color: #fff;
}
</style>
