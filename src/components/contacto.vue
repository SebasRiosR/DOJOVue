<template>
  <div>
  <h2>Contacto</h2>
  <ul>
    <li v-for="marca in marcas">{{ marca }}</li>
  </ul>
  </div>
</template>

<script>
export default {
data() {
    return {
      marcas: ["Renault", "Chevrolet", "Alfa"]
    }
  }
}
</script>

<style>
</style>

