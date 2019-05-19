<template>
    <div class="home">
      <TodayRecommend/>
      <NewMusic/>
      <SwpierBanner/>
      <MusicListNav/>
      <keep-alive>
        <router-view/>
      </keep-alive>
    </div>
</template>

<script>
  import TodayRecommend from "../components/Today_Recommend"
  import NewMusic from "../components/New_Music"
  import SwpierBanner from "../components/Swiper_Banner"
  import MusicListNav from "./musiclist/musit_listnav"

    export default {
      name: "home",
      components:{
        TodayRecommend,
        NewMusic,
        SwpierBanner,
        MusicListNav
      }
    }
</script>

<style scoped>

</style>
