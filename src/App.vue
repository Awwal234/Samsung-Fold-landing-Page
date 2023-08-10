<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <RouterView />
</template>

<style>
@font-face {
  font-family: 'Samsung Sharp Sans';
  src: local('Samsung Sharp Sans'), url(./fonts/samsungsharpsans.otf) format('truetype');
}

@font-face {
  font-family: 'SamsungOne';
  src: local('SamsungOne'), url(./fonts/SamsungOne-400.ttf) format('truetype');
}

.samsungsharp {
  font-family: 'Samsung Sharp Sans';
}

.samsungone {
  font-family: 'SamsungOne';
}
</style>
