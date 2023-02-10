<template xmlns="http://www.w3.org/1999/html">
    <ul class="nav nav-pills menu-bar">
      <div>
      <li class="nav-item" v-for="item in items">
      <a style="text-align: center;" class="nav-link rounded-circle border" :href="'#' + item.title">{{ item.title }}</a></li>
      </div>
    </ul>
</template>

<script>
export default {
  name: "headResp1",
  data() {
    return {
      items: [{ title:'Home',},{ title:'About us' }]


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