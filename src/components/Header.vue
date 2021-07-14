<template>
  <header>
      <div class="container">
          <div class="logo">Boolflix</div>
          <input type="text" placeholder="cerca"
          v-model="ricercatesto" 
          @keyup="$emit(ricerca , 'ricercatesto')">
      </div>
  </header>
</template>

<script>
export default {
    name: "Header",
    data(){
        return{
            ricercatest:''
        }
    }
}
</script>

<style scoped lang="scss">

</style>