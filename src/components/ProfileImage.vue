<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  image: String, 
});
</script>

<template>
<img
      :src="image"
      class="profile"
      alt="profile"
    />
</template>

<style scoped>

</style>