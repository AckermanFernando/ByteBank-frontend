<template>
  <div id="app">

      <BarraNavegacao></BarraNavegacao>

    <router-view />
  </div>
</template>

<script>
import BarraNavegacao from '@/components/BarraNavegacao.vue';

export default {
  components: { BarraNavegacao },
};
</script>
