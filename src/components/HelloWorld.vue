<template>
  <q-page class="flex flex-center">
    <!-- <img alt="Quasar logo" src="../assets/logo.png"> -->
    <q-select
      v-model="model"
      :options="options"
      label="bro"
    >
    </q-select>
    <q-icon class="fal fa-home"></q-icon>
  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'HelloWorld',

  data () {
    return {
      model: null,
      options: [
        'Google', 'Facebook', 'Twitter', 'Apple', 'Oracle'
      ]
    }
  }
   
}
</script>
