<template lang="html">
  <div v-if="country">
    <h3>{{country.name}}</h3>
    <p>Capital city: {{country.capital}}</p>
    <p>Population: {{country.population | formatNumber}}</p>
    <img :src="country.flag" height="120px" width="200px">
  </div>
</template>

<script>

export default {
  name: 'country-detail',
  props: ['country'],
  filters: {
    formatNumber: function(value){
      return value.toLocaleString();
    }
  }
}
</script>

<style lang="css" scoped>
</style>
