<template>
    <div>
        <hero></hero>
        <basic-elements></basic-elements>
        <examples></examples>
        <Main></Main>
    </div>
</template>
<script>
import Hero from "./components/Hero";
import Examples from "./components/Examples";
import BasicElements from "./components/BasicElements";
import CustomControls from "./components/CustomControls";
import Navigation from "./components/Navigation";
import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";
import Main from "./components/Main_form";

import Inputs from "./components/Inputs";
import DownloadSection from "./components/DownloadSection";

export default {
  name: "components",
  components: {
    Hero,
    //BasicElements,
    //Inputs,
    //CustomControls,
    //Navigation,
    JavascriptComponents,
    //Carousel,
    //Icons,
    //Examples,
    Main
    //DownloadSection
  }
};
</script>