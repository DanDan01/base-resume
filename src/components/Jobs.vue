<template>
  <h1>This is a test</h1>
</template>

<script>
  

  export default {
    components: 'Jobs',
    data(){
      return {
        computed: {
          work: [
            {title: "Title", startDate: "Dates", endDate: "End Date", city: "City", summary: "Summary"}
          ]
        }
      }
    },
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
