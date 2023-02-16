<template>
  <div>
    <NavigationBar />

    <HomeMain />

    <AboutMe />

    <CarouselWidget />

    <HomeFooter />
  </div>
</template>


<script>
import { defineComponent } from "vue";
import NavigationBar from "@/components/NavigationBar.vue";
import HomeMain from "@/components/HomeMain.vue";
import CarouselWidget from "@/components/CarouselWidget.vue";
import AboutMe from "@/components/AboutMe.vue";
import HomeFooter from "@/components/HomeFooter.vue";
export default defineComponent({
  setup() {},
  components: { NavigationBar, HomeMain, CarouselWidget, AboutMe, HomeFooter },
});
</script>
