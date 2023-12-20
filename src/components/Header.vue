<template>
    <header>
        <nav class="nav">
            <img src="../assets/images/casa.png" alt="" class="icons">
            <p class="p-nav">Home</p>
            <img src="../assets/images/code.png" alt="" class="icons">
            <p class="p-nav">Projects</p>
            <img src="../assets/images/perfil.png" alt="" class="icons">
            <p class="p-nav">About me</p>
        </nav>
    </header>
</template>
<script setup>
</script>
<style scoped>
    header {
        background: linear-gradient(#8d8d8d 0%, #141414 100%);
        padding: 20px;
        backdrop-filter: blur(5px);
        position: sticky;
        color: white;
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }
    .icons {
        width: 50px;
        height: 50px;
        margin: 0 10px 0 20px;
    }
    .nav {
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }
    .p-nav {
        margin-right: 20px;
        font-size: 2.3rem;
        display: flex;
        justify-content: center;
    }
</style>