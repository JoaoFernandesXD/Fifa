<script setup>

</script>

<template>
    <header>
        <div class="container section--container">
            <img src="../../assets/logo-fifa.png" alt="Logo oficial fifa 2022">
            <nav aria-label="Navegação principal">
                <a href="#">Início</a>
                <a href="#">Grupos</a>
                <a href="#">Partidas</a>
                <a href="#">Assistir</a>
            </nav>
        </div>
    </header>
</template>

<style scoped>

header {
    width: 100%;
    min-height: 96px;
    background-color: var(--dark-30);
    display: flex;
    justify-content: center;
    align-items: center;
}

header .container {
    width: 100%;
    max-width: 1216px;
    height: 24px;
    display: flex;
    justify-content:space-between;
    align-items: center;

}
nav {
    width: auto;
    display: flex;
    gap: 3.5rem;
}

nav a {
    font-weight: 400;
    font-size: 1.1rem;
    color: var(--dark-20);
    transition: color 0.2s;
}
nav a:hover {
    color: var(--brand-color);
}

</style>