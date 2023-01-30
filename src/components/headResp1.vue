<template>
    <ul class="nav nav-pills">
      <li class="nav-item menu-bar" v-for="item in items">
      <a  class="nav-link rounded-circle border" href="#{{ item.title }}">{{ item.title }}</a></li>
    </ul>
</template>

<script>
export default {
  name: "headResp1",
  data() {
    return {
      items: [{ title }]
    }
  }

}

</script>

<style scoped>

</style>