<template>
  <div class="specific-component-container">
    <div class="text-box">
      <h2 class="text-box-heading">Ready to get started?</h2>
      <h3 class="text-box-subheading">Sign up or contact us</h3>
    </div>

    <div class="button-box">
      <button class="orange-section-btn darker-btn">Find gift now</button>
      <button class="orange-section-btn transparent-btn">how it works</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "TheBigOrangeSection",
};
</script>

<style scoped>
.specific-component-container {
  background-color: #f7941e;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 64px 0;
}

.text-box-heading {
  font-size: 32px;
  font-weight: 600;
}

.text-box-subheading {
  font-size: 32px;
  font-weight: 400;
}

.button-box {
  display: flex;
  gap: 16px;
}

.orange-section-btn {
  text-transform: uppercase;
  font-size: 18px;
  line-height: 22px;
  padding: 16px 32px;
  /* border: none; */
  border-radius: 5px;

}

.darker-btn {
  background-color: #231f20;
  color: #fff;
  border: none;
}

.transparent-btn {
  background-color: #f7941e;
  color: #000;
  border-color: #000;
}
</style>
