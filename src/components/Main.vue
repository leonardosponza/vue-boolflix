<template>
  <main class="container">
      <section class="search">
          <h2>hai cercato</h2>
          <div class="cards">
              <card />
          </div>
      </section>
  </main>
</template>

<script>
import Card from "@/components/Card.vue";

export default {
    name: "Main",
    components:{
        Card,
    }
}
</script>

<style scoped lang="scss">

</style>