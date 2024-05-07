<template>
  <v-row class="d-flex align-center justify-center my-md-10">
    <v-col cols="auto" class="w-75">
      <h1>Protect Your Business</h1>
      <p class="mt-md-2 mb-md-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta harum ea, obcaecati
        debitis optio
        voluptate, nostrum consectetur fugit non at voluptatum nobis quis magni culpa itaque quasi molestias
        incidunt? Architecto!</p>
      <v-btn size="large">Get started</v-btn>
      <v-img class="mt-md-16" :src="BImage" />
    </v-col>
  </v-row>
</template>

<script lang="ts" setup>
import BImage from '@/assets/small-business.webp'
</script>

<style scoped lang="scss">
h1 {
  font-size: 64px;
  font-weight: 700;
}

p {
  font-size: 20px;
  line-height: 24px;
}

.v-img {
  border: 8px solid #000000;
  border-radius: 16px;
}
</style>
