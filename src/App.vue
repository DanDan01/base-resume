<template>
  <div id="app">
    <header class="header">
      <div class="header-container">
        <div class="title">
          <h3>Logo</h3>
        </div>
        <div class="navigation-container">
          <nav>
            <ul>
              <li>Summary</li>
              <li>Hobbies</li>
              <li>Job History</li>
              <li>Education</li>
              <li>Certifications</li>
            </ul>
          </nav>
        </div>
      </div>
    </header>
    <section class="Summary">
      <h2>Summary</h2>
    </section>
    <section class="hobbies">
      <h2>Hobbies</h2>
    </section>
    <section class="job-history">
      <h2>Job History</h2>
      <Jobs />
    </section>
    <section class="education">
      <h2>Education</h2>
    </section>
    <section class="certifications">
      <h1>Certifications</h2>
    </section>
  </div>
</template>

<script>
import Jobs from './components/Jobs.vue'

export default {
  name: 'App',
  components: {
    Jobs
  }
}
</script>

<style>

</style>
