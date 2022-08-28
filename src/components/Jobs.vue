<template>
  <div class="jobs-container" v-for="jobs of work" :key="jobs.order">
    <div class="title">Title: {{jobs.title}}</div>
    <div class="start-date">Start Date: {{jobs.startDate}}</div>  
    <div class="end-date">End Date: {{jobs.endDate}}</div>
    <div class="city">City: {{jobs.city}}</div> 
    <div class="state">State: {{jobs.state}}</div>
    <div class="summary">Summary: {{jobs.summary}}</div>
  </div>
</template>

<script>
  import { computed, ref } from 'vue';

  export default {
    components: 'Jobs',
    data(){
      return {
         work: ref([
            {order: "1", currentRole: false, title: "Title", startDate: "Dates", endDate: "End Date", city: "City", state: "State", summary: "Summary"}
        ])
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
