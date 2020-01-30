<template>
  <div class="monos__blackline monos__blackline--bg--color"></div>
</template>

<script>
export default {};
</script>

<style>
:root {
  --black: #24292e;
  --gray: #c0c1c3;
  --white: #ffffff;
}
.monos__blackline {
  width: 100%;
  height: 20px;
  position: relative;
  display: block;
}
.monos__blackline--bg--color {
  background-color: var(--black);
  box-shadow: 2px 0 0 2px rgba(255, 255, 255, 0.5);
}
</style>