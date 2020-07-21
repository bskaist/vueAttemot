<template>
  <h1 @mouseover="mousedOver" :style="{ color: color }">Hello World!</h1>
</template>

<script>
export default {
  name: 'EventCard',
  data() {
    return {
      color: 'black'
    }
  },
  methods: {
    mousedOver: function() {
      this.color = 'red'
    }
  }
}
</script>

<style></style>
