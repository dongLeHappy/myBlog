<template>
    <div>
      <p></p>
      <p>logo栏</p>
      <p>个人中心</p>
    </div>
</template>

<script>
    export default {
        name: "header"
    }
</script>

<style scoped lang="scss">
  div{
    width: 100%;
    background-color: #a7a3b7;
    display: flex;
    flex-direction: row;
    p{
      text-align: center;
      line-height: 30px;
      width: 33%;
      color: #fff;
    }
  }

</style>
