<template>
  <HeaderStore/>
  <SectionOne/>
  <SectionTwo/>
  <SectionThree/>
  <SectionFour/>
  <StoreFooter/>
</template>

<script>
import HeaderStore from "@/components/header";
import SectionOne from "@/components/section1";
import SectionTwo from "@/components/section2";
import SectionThree from "@/components/section3";
import SectionFour from "@/components/section4";
import StoreFooter from "@/components/StoreFooter";

export default {
  name: 'App',
  components: {
    StoreFooter,
    SectionFour,
    SectionThree,
    SectionTwo,
    SectionOne,
    HeaderStore
  }
}
</script>

<style>
@font-face {
  font-family: "Apercu";
  src: local("Apercu"), url("./fonts/Apercu.ttf") format("truetype");
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
