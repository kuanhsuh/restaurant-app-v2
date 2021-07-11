<template>
  <v-bottom-navigation>
    <v-btn to="/contact">
      <span>聯絡</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>

    <v-btn to="/menu">
      <span>菜單</span>

      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn to="/">
      <span>商店</span>

      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn to="/cart">
      <span>購物車</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>

<script>
export default {
  name: "BottomNav",
};
</script>
