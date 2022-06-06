<template>
  <div class="specific-component-container">
    <div class="card" style="width: 18rem">
      <img :src="require(`@/assets/${imgSrc}`)" class="card-img-top" />

      <div class="card-body">
        <h5 class="card-title">{{ cardTitle }}</h5>
        <a href="#" class="see-more-link">See More ›</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "GiftCard",
  props: {
    imgSrc: String,
    cardTitle: String,
  },
};
</script>

<style scoped>
.see-more-link {
  text-decoration: none;
  color: black;
}

.see-more-link:hover {
  color: #dc2626;
}
</style>
