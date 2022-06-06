<template>
  <div class="specific-component-container">
    <div class="container-fluid text-box">
      <h3 class="best-blog-ever-heading">Our Best Blogs Ever</h3>
      <p class="best-blog-ever-subheading">
        “Try our blog to find the best tips and tricks to select your gift”
      </p>
    </div>

    <div class="container silly-couple-card">
      <div class="img-box">
        <img :src="require(`@/assets/${imgSrc}`)" alt="silly-couple" />
      </div>

      <div class="content-box">
        <div class="content-text-box">
          <p class="mr-john-doe">
            <small>Mr. John Doe</small>
          </p>
          <h2 class="content-box-heading">The best way to wish your wife</h2>
          <a href="#" class="read-more-link">Read More ›</a>
        </div>
      </div>
    </div>

    <div class="container feature-cards">
      <FeatureCard
        featureHeading="Database to find the gifts for your girlfriend"
        featureDetails="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore..."
      />
      <FeatureCard
        featureHeading="How Artificial Intelligence read your mind to find the best gift"
        featureDetails="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore..."
      />
    </div>
  </div>
</template>

<script>
import FeatureCard from "./FeatureCard.vue";

export default {
  name: "OurBestBlogsEver",
  props: {
    imgSrc: String,
  },
  components: {
    FeatureCard,
  },
};
</script>

<style scoped>
.specific-component-container {
  padding: 30px 0;
}

.text-box {
  margin-bottom: 72px;
}

.best-blog-ever-heading {
  text-align: center;
  font-size: 32px;
  line-height: 38px;
  margin-bottom: 23px;
}

.best-blog-ever-subheading {
  text-align: center;
  font-size: 18px;
  line-height: 135.94%;
  margin-bottom: 64px;
}

.silly-couple-card {
  display: grid;
  grid-template-columns: 1fr 3fr;
  margin-bottom: 40px;
}

.content-box {
  background-color: #231f20;
  color: #fff;
}

.content-text-box {
  padding-left: 78px;
  padding-top: 64px;
  /* padding-bottom: 48px; */
}

.mr-john-doe {
  margin-bottom: 26px;
  font-size: 14px;
}

.content-box-heading {
  margin-bottom: 60px;
  font-size: 48px;
}

.read-more-link {
  text-decoration: none;
  color: #fff;
  font-weight: 300;
  font-size: 18px;
}

.read-more-link:hover {
  color: #f7941e;
}

.feature-cards {
  display: flex;
  gap: 15px;
}
</style>