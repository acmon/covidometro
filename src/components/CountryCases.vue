<script setup>
</script>

<template>
  <div class="div-country">
    <h2>Africa do sul</h2>
    <div class="div-cases">
      <div class="div-case-item">
        <div class="case-title">Total de casos</div>
        <div class="case-value">36.480.487</div>
      </div>
      <div class="div-case-item">
        <div class="case-title">Mortes</div>
        <div class="case-value">480.487</div>
      </div>
      <div class="div-case-item">
        <div class="case-title">Fatalidade</div>
        <div class="case-value">2,05%</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.div-country{
  border: 1px solid #e2e2e2;
  border-radius: 5px;
  margin: 0 1rem;
  text-align: center;
  background-color: #FFF;
}


.case-title {
  margin-top: 1rem;
}

.case-value {
  color: #ef6261;
  font-size: 1.5rem;
}

@media (min-width: 815px) {
  .div-country {
    margin: 0 15rem;
  }

  .div-cases {
    display: flex;
    justify-content: space-between;
  }
}

@media (min-width: 1145px) {
  .div-cases {
    display: flex;
    justify-content: space-between;
    padding: 0 10rem;
  }
}

</style>
