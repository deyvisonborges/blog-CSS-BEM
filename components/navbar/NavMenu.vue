<template>
  <nav class="monos__navmenu monos__navmenu--bg">
    <ul class="monos__navmenu--left monos__navmenu--pd">
      <li>
        <a href>Home</a>
      </li>
      <li>
        <a href>Explore</a>
      </li>
      <li>
        <a href>...</a>
      </li>
    </ul>
    <ul class="monos__navmenu--right monos__navmenu--pd">
      <li>
        <a href>Editar perfil</a>
      </li>
      <li>
        <a href>Perfil</a>
      </li>
      <li>
        <a href>Encerrar sessão</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {

};
</script>

<style>
:root {
  --black: #24292e;
  --gray: #f5f5f5;
  --white: #ffffff;
  --shadow: -2px 1px 4px 0px #ccc;
}
.monos__navmenu {
  width: 100%;
  position: relative;
  display: inline-block;
}
.monos__navmenu--bg {
  background-color: var(--gray);
  box-shadow: var(--shadow);
}
.monos__navmenu--pd {
  position: relative;
  display: inline-block;
}
.monos__navmenu--left {
  width: 50%;
  padding: 10px;
}
.monos__navmenu--right {
  width: 50%;
  padding: 10px;
  float: right;
}
.monos__navmenu--left li,
.monos__navmenu--right li {
  list-style: none;
  display: inline-block;
  margin-right: 15px;
}
.monos__navmenu--right li {
  justify-content: flex-end;
  list-style: none;
}
.monos__navmenu--right li:last-child {
  margin-right: 0;
}
.monos__navmenu--left li a,
.monos__navmenu--right li a {
  color: #24292e;
  display: block;
  text-decoration: none;
}

</style>