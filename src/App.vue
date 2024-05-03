<script setup>
  import Vheader from "./components/Vheader.vue";
  import Vfooter from "./components/Vfooter.vue";
  import Vpromo from "./components/Vpromo.vue";
  import Vclass from "./components/Vclass.vue";
  import Vhistory from "./components/Vhistory.vue";
  import Vpossibility from "./components/Vpossibility.vue";
  import Videa from "./components/Videa.vue";
  import Vreview from "./components/Vreview.vue";
</script>

<template>
  <vheader/>
      <main>
        <vpromo />
        <vclass />
        <vhistory />
        <vpossibility />
        <videa />
        <vreview />
    </main>
   <vfooter/>
</template>

<style scoped>

</style>
