<template>
  <div class="my-name">
    <h1>Hello, my name is {{ name }}!</h1>
  </div>
</template>

<script>
export default {
  name: 'MyName',
  data() {
    return {
      name: 'Donghao Qin'
    }
  }
}
</script>

<style scoped>
.my-name {
  text-align: center;
  margin-top: 20px;
}
</style>
