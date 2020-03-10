<template>
  <div class="stream-info">
    <h1>{{ msg }}</h1>
    <p>
      Streaming link will be made available here shortly before meetup start:
    </p>
    <div v-if="live">
      <a href="https://youtube.com/link" target="_blank" rel="noopener">YouTube Live Stream</a>
    </div>
    <div v-else>. . .</div>
  </div>
</template>

<script>
export default {
  name: 'StreamInfo',
  data() {
    return {
      live: false
    }
  }
}
</script>

<style scoped>
a {
  color: #00aed9;
}
</style>
