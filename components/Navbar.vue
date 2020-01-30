<template>
  <div class="monos__navbar">
      <blackline/>
      <navmenu/>
  </div>
</template>

<script>
import blackline from '../components/navbar/BlackLine';
import navmenu from '../components/navbar/NavMenu';

export default {
    components: {
        blackline, 
        navmenu
    }
}
</script>

<style>
.monos__navbar {
    width: 100%;
    position: relative;
}
</style>