<template>
  <div class="home">
    <h1>This is a home page</h1>
    <Progress />
  </div>
</template>

<script>
import Progress from '../components/Progress.vue'

export default {
  name: 'HomeView',
  components: {
    Progress,
  },
  data() {
    return {}
  },
}
</script>

<style scoped></style>
