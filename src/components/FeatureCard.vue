<template>
  <div class="feature-card">
    <h3 class="feature-heading">
      {{ featureHeading }}
    </h3>
    <p class="feature-details">
      {{ featureDetails }}
    </p>
    <a href="#" class="read-more-link">Read More ›</a>
  </div>
</template>

<script>
export default {
  name: "FeatureCard",
  props: {
    featureHeading: String,
    featureDetails: String,
  },
};
</script>

<style scoped>
.feature-card {
  width: 50%;
  padding: 7%;
  box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.1);
}

.feature-heading {
  margin-bottom: 15px;
  font-size: 18px;
  font-weight: 700;
}

.feature-details {
  margin-bottom: 32px;
}

.read-more-link {
  text-decoration: none;
  color: #000;
  font-weight: 300;
  font-size: 18px;
}

.read-more-link:hover {
  color: #f7941e;
}
</style>
