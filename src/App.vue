<script setup>
import Header from "@/components/header.vue";
import Footer from "@/components/footer.vue";
import Body from "@/components/body.vue";
</script>

<template>
    <Header title="{{ items.title }}"/>

  <Body/>

  <Footer/>

</template>

<style scoped>

</style>

<script>

export default {
  name: "headResp1",
  data() {
    return {
      items: [{ title:'home' },{ title:'About us' }]
    }
  }

}

</script>