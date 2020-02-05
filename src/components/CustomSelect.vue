<template>
  <v-col class="sample-style">
    <v-select name="hoge" :items="items" v-model="selected"></v-select>
  </v-col>
</template>

<style scoped>
  .sample-style {
    background-color: rgb(163, 159, 163);
  }
</style>

<script>

export default {
  name: 'CustomSelect',
  props: ['items','selected'],
}

</script>