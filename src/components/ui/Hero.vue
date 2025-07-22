<script setup>

</script>

<template>
     <section class="hero">
        <img src="../../assets/background-bola.jpg">
        <div class="overlay">
            <img src="../../assets/logo copa.svg">
        </div>
    </section>
</template>


<style scoped>
.hero {
    width: 100%;
    height: 575px;
    position: relative;
}
.hero img {
   width: 100%;
   height: 100%;
   object-fit: cover;
   display: block;

}
.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #8D1B3DB2;
    z-index: 1;
    display: flex;
    justify-content: center;
    align-items: center;
}
.overlay img {
    width: 100%;
    max-width: 348px;
    height: 417px;
    object-fit: cover;
}


</style>