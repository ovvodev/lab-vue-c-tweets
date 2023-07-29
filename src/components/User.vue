<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  user : {
    name:String,
    handle: String
    }
});
</script>

<template>
    <span class="user">
          <span class="name">{{ user.name }}</span>
          <span class="handle">{{ user.handle }}</span>
    </span>
</template>

<style scoped>

</style>