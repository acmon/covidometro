<script setup>
import CountryFilter from './CountryFilter.vue'
import CountryCases from './CountryCases.vue'
</script>

<template>
  <CountryFilter class="filter" />
  <CountryCases class="country" />
</template>

<style scoped>
.filter {
  margin-bottom: 2rem;
}

.country {
  margin-bottom: 1rem;
}
</style>
