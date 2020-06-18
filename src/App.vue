<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
import Layout from '@/layout'  // 把这行代码注释掉就可以页面就不会出现空白，不知道为什么添加这一行代码就出现问题了
export default {
  name: 'App'
}
</script>
