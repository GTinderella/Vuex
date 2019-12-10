<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
@keyframes myfirst {
  from {
    width: 100px;
    background: red;
  }
  to {
    width: 200px;
    background: yellow;
  }
}
h1 {
  animation: myfirst 5s;
  width: 100px;
  color: rgb(75, 131, 75);
  white-space: nowrap;
  text-overflow: ellipsis;
}
</style>
