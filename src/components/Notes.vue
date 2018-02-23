<template>
  <div class="notes">
    <span>{{ counter }}</span>
    <button @click="counter += 1">+1s</button>
  </div>
</template>

<script>
export default {
  name: 'Notes',
  data () {
    return {
      counter: 0,
    }
  }
}
</script>
