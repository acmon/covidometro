<script setup>
</script>

<template>
  <div class="filter">
    <h2>Filtrar dados sobre um país</h2>
    <input class="input" type="text" placeholder="Digite o nome do país">
  </div>
</template>

<style scoped>
.filter{
  border: 1px solid #e2e2e2;
  border-radius: 5px;
  margin: 0 1rem;
  text-align: center;
  background-color: #FFF;
}

.input{
  border: 0;
  border-bottom: 1px solid red;
  width: 40rem;
  margin-bottom: 2rem;
}

input:focus{
    outline: none;
}

@media (max-width: 1290px) {
  .input{
    width: 15rem;
  }
}

@media (min-width: 815px) {
  .filter {
    margin: 0 15rem;
  }
}
</style>
