<template>
  <div class="bg-site h-screen">
  
    <!-- <navHeader /> -->


    <div class="text-white mx-10 pt-10 font-bold text-3xl">
      Fully CSS UI components and animations to integrate into any website. 
    </div>

    <div class="grid grid-cols-1 lg:grid-cols-3 2xl:grid-cols-1 pt-10 gap-x-10 gap-y-10 px-10">
      <cattoCard />
      <softwindCard />
      <animationsCard />
    </div>

      <cattoFooter />
  </div>

</template>

<style>

</style>

<script>
import navHeader from "../components/navHeader";
import cattoCard from "../components/cattoCard";
import softwindCard from "../components/softwindCard";
import animationsCard from "../components/animationsCard";
import cattoFooter from "../components/cattoFooter";

export default {
  components:{
    navHeader,
    cattoCard,
    softwindCard,
    animationsCard,
    cattoFooter
  }
}
</script>