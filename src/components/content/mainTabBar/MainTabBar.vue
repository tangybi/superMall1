<template>
  <div>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="Pink">
        <img src="~assets/img/tabbar/home.svg" alt="" slot="item-icon" />
        <img
          src="~assets/img/tabbar/home-active.svg"
          alt=""
          slot="item-icon-active"
        />
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="Pink">
        <img src="~assets/img/tabbar/category.svg" alt="" slot="item-icon" />
        <img
          src="~assets/img/tabbar/category-active.svg"
          alt=""
          slot="item-icon-active"
        />
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="Pink">
        <img src="~assets/img/tabbar/Cart.svg" alt="" slot="item-icon" />
        <img
          src="~assets/img/tabbar/Cart-active.svg"
          alt=""
          slot="item-icon-active"
        />
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="Pink">
        <img src="~assets/img/tabbar/profile.svg" alt="" slot="item-icon" />
        <img
          src="~assets/img/tabbar/profile-active.svg"
          alt=""
          slot="item-icon-active"
        />
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
import TabBar from "components/common/tabbar/tabbar"
import TabBarItem from "components/common/tabbar/tabbaritem"
export default {
  name: 'MainTabBar',
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style>
</style>
