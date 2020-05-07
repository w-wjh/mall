<template>
  <TabBar>
      <TabBarItem path="/home" activeColor="#81adff">
        <img src="~assets/img/tabbar/home.svg" slot="item-icon">
        <img src="~assets/img/tabbar/home-fill.svg" slot="item-icon-active">
        <div slot="item-text">首页</div>
      </TabBarItem>
      <TabBarItem path="/category" activeColor="#81adff">
        <img src="~assets/img/tabbar/all.svg" slot="item-icon">
        <img src="~assets/img/tabbar/all-fill.svg" slot="item-icon-active">
        <div slot="item-text">分类</div>
      </TabBarItem>
      <TabBarItem path="/cart" activeColor="#81adff">
        <img src="~assets/img/tabbar/cart-Empty.svg" slot="item-icon">
        <img src="~assets/img/tabbar/cart-Empty-fill.svg" slot="item-icon-active">
        <div slot="item-text">购物车</div>
      </TabBarItem>
      <TabBarItem path="/profile" activeColor="#81adff">
        <img src="~assets/img/tabbar/account.svg" slot="item-icon">
        <img src="~assets/img/tabbar/account-fill.svg" slot="item-icon-active">
        <div slot="item-text">我的</div>
      </TabBarItem>
    </TabBar>
</template>

<script>

  import TabBar from 'components/common/tabbar/TabBar'
  import TabBarItem from 'components/common/tabbar/TabBarItem'

  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>