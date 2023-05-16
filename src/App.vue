<script setup>
</script>

<template>
  <header>
    <nav class="nav">
      <div>
        <img src="./assets/images/logo.png" alt="logo da página" />
      </div>
    </nav>
  </header>

  <main>

  </main>
</template>

<style scoped>
.nav {
  background-color: #fff;
  height: 4rem;
  display: flex;
  justify-content: center;
  align-items: center;
  box-shadow: 0px 15px 10px -15px rgb(207, 207, 207);
}

@media (min-width: 768px) {
  .nav {
    padding-left: 5rem;
    justify-content: space-between;
    align-items: center;
  }
}
</style>
