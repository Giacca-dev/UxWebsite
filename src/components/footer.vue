<template>
  <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4">
    <TopDivider/>
    <div class="col-md-6 d-flex justify-content-center">
      <ul class="nav justify-content-center navbar-nav m-2" v-for="item in items">
        <li class="nav-item"><a :href="'#' + item.title" class="nav-link text-muted">{{ item.title }}</a></li>
      </ul>
    </div>

    <ul class="nav col-md-6 justify-content-end list-unstyled d-flex">
      <li class="ms-3"><a class="text-muted" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#twitter"></use></svg></a></li>
      <li class="ms-3"><a class="text-muted" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#instagram"></use></svg></a></li>
      <li class="ms-3"><a class="text-muted" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#facebook"></use></svg></a></li>
    </ul>
  </footer>
</template>

<script>
import TopDivider from "@/components/topDivider.vue";
export default {
  name: "footer",
  components: TopDivider,
  data() {
    return {
      items: [{ title:'Home',},{ title:'About us' }]


    }
  }
}
</script>

<style scoped>

</style>