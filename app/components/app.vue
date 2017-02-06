<template lang="html">
  <div class="">
    {{message}}
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hello World'
    }
  },
	render: h => h(App)
}
</script>

<style lang="css">
</style>
