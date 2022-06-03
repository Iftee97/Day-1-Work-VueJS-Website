<template>
  <div class="specific-component-container">
    <div class="container-fluid">
      <h3 class="gift-heading">Gifts for all Occasions</h3>
      <p class="gift-subheading">
        “Try our web app to find the best gifts for all occasions”
      </p>

      <div class="gift-cards">
        <GiftCard imgSrc="birthday.png" cardTitle="Birthday" />
        <GiftCard imgSrc="anniversary.png" cardTitle="Anniversary" />
        <GiftCard imgSrc="valentines-day.png" cardTitle="Valentine's Day" />
        <GiftCard imgSrc="christmas.png" cardTitle="Christmas" />
      </div>
    </div>
  </div>
</template>

<script>
import GiftCard from "./GiftCard.vue";

export default {
  name: "GiftsForAllOccasions",
  components: {
    GiftCard,
  },
};
</script>

<style scoped>
.specific-component-container {
  padding: 30px 0;
}

.gift-heading {
  text-align: center;
  font-size: 32px;
  line-height: 38px;
  margin-bottom: 23px;
}

.gift-subheading {
  text-align: center;
  font-size: 18px;
  line-height: 135.94%;
  margin-bottom: 64px;
}

.gift-cards {
  display: flex;
  gap: 80px;
  justify-content: center;
  align-items: center;
}
</style>