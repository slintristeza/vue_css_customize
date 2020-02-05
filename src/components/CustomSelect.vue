<template>
  <v-col class="height-style width-style">
    <v-select name="hoge" :items="items" v-model="selected"></v-select>
  </v-col>
</template>

<style scoped>
  @import './sample.css';
  .height-style ::v-deep .v-input__slot {
      height: 100px;
  }
</style>

<script>

export default {
  name: 'CustomSelect',
  props: ['items','selected'],
}

</script>