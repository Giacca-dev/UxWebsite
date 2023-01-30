<template>
  <header class="d-flex flex-wrap justify-content-center py-3 border-bottom">
    <a class="d-flex align-items-center ms-4 mb-3 mb-md-0 me-md-auto text-dark text-decoration-none" href="">
      <span class="fs-1 fw-bold">Traveller</span>
      <head-resp1 />
    </a>
  </header>
</template>

<script>
  import HeadResp1 from "@/components/headResp1.vue";


  let bool=true;
export default {
  name: "header",
  components: {HeadResp1}
}
</script>

<style scoped>

</style>