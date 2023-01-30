<template>
    <ul class="nav nav-pills menu-bar">
      <li class="nav-item" v-for="item in items">
      <a  class="nav-link rounded-circle border" href="#">{{ item.title }}</a></li>
    </ul>
</template>

<script>
export default {
  name: "headResp1",
  data() {
    return {
      items: [{ title:'Home' },{ title:'About us' }]
    }
  }

}

</script>

<style>
.menu-bar{
  position: fixed;
  left: 2%;
  bottom: 50%;
}
</style>