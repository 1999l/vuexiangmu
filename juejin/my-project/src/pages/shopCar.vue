<template>
  <div>
    <shopCar />
    <shopping />
  </div>
</template>
<script>
import shopCar from "../components/shopCar-card.vue";
import shopping from "../components/shopping.vue";
export default {
  components: {
    shopCar,
    shopping
  }
};
</script>