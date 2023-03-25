<!-- Please remove this file from your project -->
<template>
  <div class="flex flex-col w-full h-screen ">
    <div class="flex hero" :style="{'background-image': `url(${require('@/static/assets/img/bg-main-mobile.png')})`}"> d
      <nuxt-img src="/assets/img/bg-card-back.png" width="200px" height="100px" />
    </div>
    <div class="flex w-full pt-12"></div>
  </div>
</template>

<script>
  export default {
    name: 'NuxtTutorial'
  }

</script>
