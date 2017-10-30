<template>
  <div id="home">
    <h1>{{ msg }}</h1>
    <ul>
      <li><router-link to="/one">点我跳转到第一页</router-link></li>
      <li><router-link to="/two">点我跳转到第二页</router-link></li>
    </ul>
  </div>
</template>

<script type="text/javascript">
export default {
  data () {
    return {
      msg: '我是首页-home.'
    }
  }
}
</script>
