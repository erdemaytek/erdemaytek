<template>
  <div>
      <ul>
          <li  v-if="/blog/.test(item.regularPath)" v-for="item in this.$site.pages" :key="item">  <a :href="item.regularPath"> {{ item.title }}</a>  </li>
      </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>