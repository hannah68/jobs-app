<template>
  <h1>Job details page</h1>
  <p>The job id id: {{id}}</p>
</template>

<script>
export default {
  props: ['id'],
  // for getting the id we can use like below through route or like above through props
  // data(){
  //   return{
  //     id: this.$route.params.id
  //   }
  // }
}
</script>

<style>

</style>