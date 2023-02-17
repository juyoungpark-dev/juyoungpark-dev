<template>
  <div>
    <NavigationBar />
    <HomeMain />
    <ModalWidget />
    <AboutMe />
    <!-- <CarouselWidget /> -->
    <!-- <HomeFooter /> -->
  </div>
</template>


<script>
import { defineComponent } from "vue";
import NavigationBar from "@/components/NavigationBar.vue";
import HomeMain from "@/components/HomeMain.vue";
import AboutMe from "@/components/AboutMe.vue";
import ModalWidget from "@/components/ModalWidget.vue";
// import CarouselWidget from "@/components/CarouselWidget.vue";
// import HomeFooter from "@/components/HomeFooter.vue";

export default defineComponent({
  setup() {},
  components: {
    NavigationBar,
    HomeMain,
    AboutMe,
    // CarouselWidget,
    // HomeFooter,
    ModalWidget,
  },
});
</script>
