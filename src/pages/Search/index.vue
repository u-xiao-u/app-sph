<template>
  <div>
    <h1>params参数---{{$route.params.keyword}}----{{k}}</h1>
    <h2>query参数---{{$route.query.k}}----{{keyword}}</h2>
  </div>
</template>

<script>
export default {
  name: 'Search',
  props: ['keyword', 'k', 'keyword']
}
</script>

<style>

</style>