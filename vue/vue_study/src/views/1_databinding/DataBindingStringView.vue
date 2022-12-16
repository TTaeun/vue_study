<template>
    <div>
        <h1>Hello {{ userName }}</h1>
        <p></p>
    </div>
</template>
<script>
export default {
  data() {
    return {
      userName: 'John Park'
    }
  }
}
</script>
<style scoped>
.text-red {
    color: red
}
</style>
