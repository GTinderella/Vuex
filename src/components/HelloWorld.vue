<template>
    <div>
        <h1>vuex-shopCart</h1>
        <div class="shop-listbox">
            <shop-list/>
        </div>
        <h2>已选商品</h2>
        <div class="shop-cartbox">
            <shop-cart/>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="less">

</style>
