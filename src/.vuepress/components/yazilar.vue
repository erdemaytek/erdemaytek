<template>
  <div>
      <ul>
          <li v-for="item in this.$site.pages" :key="item">  <a :href="item.regularPath"> {{ item.title }}</a>  </li>
      </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>