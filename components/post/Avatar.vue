<template>
    <div class="monos__avatar">
        <div class="monos__image monos__image--bg-color">o</div>
        <div class="monos__autoria">
            <div class="monos__nome">Deyvison</div>
            <div class="monos__data">30.01.2020</div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.monos__avatar {
    width: 100%;
    position: relative;
    display: inline-block;
}
.monos__image {
    display: inline-block;
    position: relative;
    width: 50px;
    height: 50px;
}
.monos__image--bg-color {
    background-color: blue;
    border-radius: 20px;
}
.monos__autoria {
    display: inline-block;
    position: relative;
}
</style>