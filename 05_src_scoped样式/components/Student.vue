<template>
  <div class="demo">
    <h2 class="title">学生姓名:{{name}}</h2>
    <h2 class="atguigu">学生性别:{{sex}}</h2>
  </div>
</template>

<script>


export default {
    name:'Student',
    data(){
        return{
           name:'理塘丁真',
           sex:'男'
        }
    },
}
</script>

<style lang="less">
 .demo{
  background-color: orange;
  .atguigu{
    font-size: 40px;
  }
 }
</style>