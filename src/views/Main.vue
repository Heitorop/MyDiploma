<template>
  <v-container class="fill-height">
    <v-responsive class="align-center text-center fill-height">
      <FirstSlide />
      <SecondSlide />
      <ThirdSlide />
    </v-responsive>
  </v-container>

</template>

<script lang="ts" setup>
import FirstSlide from '@/components/FirstSlide.vue'
import SecondSlide from '@/components/SecondSlide.vue';
import ThirdSlide from '@/components/ThirdSlide.vue';
</script>
