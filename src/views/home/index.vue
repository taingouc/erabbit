<template>
  <div class="home-entry">
    <div class="container">
      <!-- 首页入口 -->
      <div class="home-entry">
        <!-- 左侧分类 -->
        <HomeCategory></HomeCategory>
        <!-- 轮播图 -->
        <HomeBanner></HomeBanner>
      </div>
    </div>
    <!-- 新鲜好物 -->
    <HomeNew></HomeNew>
    <!-- 人气推荐 -->
    <HomeHot></HomeHot>
    <!-- 热门品牌 -->
    <HomeBrand></HomeBrand>
    <!-- 商品区域 -->
    <HomeProduct></HomeProduct>
    <!-- 最新专题 -->
    <HomeSpecial></HomeSpecial>
  </div>
</template>

<script>
import HomeCategory from './components/home-category'
import HomeBanner from './components/home-banner'
import HomeNew from './components/home-new'
import HomeHot from './components/home-hot'
import HomeBrand from './components/home-brand'
import HomeProduct from './components/home-product'
import HomeSpecial from './components/home-special'
export default {
  name: 'Home',
  components: {
    HomeCategory,
    HomeBanner,
    HomeNew,
    HomeHot,
    HomeBrand,
    HomeProduct,
    HomeSpecial
  }
}
</script>

<style lang="less" scoped></style>
