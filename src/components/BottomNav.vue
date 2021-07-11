<template>
  <v-bottom-navigation grow :value="value"
    color="primary">
    <v-btn to="/contact" text  height="100%">
      <span>聯絡</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>

    <v-btn to="/menu" text height="100%">
      <span>菜單</span>

      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn to="/" text height="100%">
      <span>商店</span>

      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn to="/cart" text height="100%">
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
