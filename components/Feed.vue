<template>
  <div class="monos__feed">
      <div class="monos__feed--post monos__feed--post--style">
        <post/>
      </div>
  </div>
</template>

<script>
import post from '../components/post/Post';

export default {
  components: {
    post
  }
}
</script>

<style>
.monos__feed {
  width: 100%;
  height: 100vh;
  position: relative;
  padding:  20px 200px;
}
.monos__feed--post {
  width: 100%;
  padding: 10px 15px;
  position: relative;
  display: inline-block;
}
.monos__feed--post--style {
  background-color: #f5f5f5;
  box-shadow: 2px 0px 10px 0px #ccc;
}
</style>