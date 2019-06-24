<template>
    <div class="layout-wrap">
        <AppAside/>
        <AppHeader/>
        <!-- Home、内容管理、粉丝管理。。。。都显示到这里 -->
    </div>
</template>
<script>
import AppAside from './components/AppAside'
import AppHeader from './components/AppHeader'

export default {
  name: 'Applayout',
  components: {
    AppAside,
    AppHeader
  },
  data() {
    return {}
  }
}
</script>
<style lang="less" scoped>

</style>
