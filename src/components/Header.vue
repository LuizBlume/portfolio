<template>
  <header>
    <nav class="nav">
      <img src="../assets/images/casa.png" alt="" class="icons" />
      <p class="p-nav">Home</p>
      <img src="../assets/images/code.png" alt="" class="icons" />
      <p class="p-nav">Projects</p>
      <img src="../assets/images/perfil.png" alt="" class="icons" />
      <p class="p-nav">About me</p>
    </nav>
  </header>
</template>
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
@media (max-width: 425px) {
  header {
    padding: 10px;
    justify-content: center;
  }
  .icons {
    width: 40px;
    height: 40px;
    margin: 0 5px 0 10px;
  }
  .p-nav {
    margin-right: 10px;
    font-size: 1.5rem;
  }
}
@media (min-width: 426px) and (max-width: 768px) {
  .icons {
    width: 40px;
    height: 40px;
    margin: 0 5px 0 10px;
  }
  .p-nav {
    margin-right: 10px;
    font-size: 1.5rem;
  }
}
@media (min-width: 769px) and (max-width: 1024px) {
  .icons {
    width: 40px;
    height: 40px;
    margin: 0 5px 0 10px;
  }
  .p-nav {
    margin-right: 10px;
    font-size: 1.8rem;
  }
}
</style>