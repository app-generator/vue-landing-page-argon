<template>
    <div>
        <hero-index></hero-index>
        <index-info></index-info>
    </div>
</template>
<script>
import HeroIndex from "./components/HeroIndex";
import BasicElements from "./components/BasicElements";
import Inputs from "./components/Inputs";
import CustomControls from "./components/CustomControls";
import Navigation from "./components/Navigation";
import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";
import IndexInfo from "./components/IndexInfo";
import Examples from "./components/Examples";
import DownloadSection from "./components/DownloadSection";

export default {
  name: "appindex", 
  components: {
    HeroIndex,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    IndexInfo,
    Examples,
    DownloadSection
  }
};
</script>
