<template>
    <div>
        <inicio></inicio>
        <teste></teste>
        <parallax></parallax>
        <cards></cards>
        <img-bg></img-bg>
        <clean></clean>
    </div>
</template>
<script>
  import Inicio from '@/components/home/sections/Inicio.vue'
  import Teste from '@/components/home/sections/Teste.vue'
  import Parallax from '@/components/home/sections/Parallax.vue'
  import Cards from '@/components/home/sections/Cards.vue'
  import ImgBg from '@/components/home/sections/ImgBg.vue'
  import Clean from '@/components/home/sections/Clean.vue'

  export default {
    name: 'home',
    components: {
      Inicio,
      Teste,
      Parallax,
      Cards,
      ImgBg,
      Clean
    }
  }
</script>
<style scoped>
    .white-text {
        color: azure;
    }
</style>