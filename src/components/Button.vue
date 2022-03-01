

<template>
  <button type="button" class="btn btn-outline-primary">{{text}}</button>
</template>

<script>
export default {
  name: 'Button',
  props: {
    text: String,
    type: String
  }
}
</script>

<style scoped>
</style>
