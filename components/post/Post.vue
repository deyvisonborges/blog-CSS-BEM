<template>
  <div class="monos__post">
    <div class="monos__new__post">
      <ul class="monos__quantity__feeds">
        <li>5</li>
        <li>feeds</li>
      </ul>
      <button class="button button--state-success" type="submit">
        Novo post
      </button> 
    </div>
    <avatar/>
  </div>
</template>

<script>
import avatar from './Avatar';
export default {
    name: 'post',
    components: {
      avatar
    }
}
</script>

<style>
.monos__post {
  width: 100%;
  position: relative;
  display: inline-block;
}
.monos__new__post {
  padding: 0 20px;
}
.monos__quantity__feeds {
  width: 80%;
  height: 20px;
  display: inline-block;
}
.monos__quantity__feeds li{
  list-style: none;
  display: inline-block;
  margin-right: 15px;
  margin-left: 15px;
}
.button {
  width: 15%;
  display: inline-block;
  border-radius: 3px;
	padding: 7px 12px;
	border: 1px solid #D5D5D5;
  font: 700 13px/18px;
}
.button--state-success {
	color: #FFF;
	background: #569E3D linear-gradient(#79D858, #569E3D) repeat-x;
	border-color: #4A993E;
}
.button--state-danger {
	color: #900;
}
</style>