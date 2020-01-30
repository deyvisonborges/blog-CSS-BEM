<template>
  <div class="monos">
      <navbar/>
      <feed/>
  </div>
</template>

<script>
import navbar from '../components/Navbar';
import feed from '../components/Feed';

export default {
    components: {
        navbar,
        feed
    }
}
</script>

<style>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Noto Sans', sans-serif;
    will-change: contents;
}
</style>