<template>
  <div>
    <HeaderTwo/>
    <SliderThree/>
    <ServiceTwo/>
    <About/>
    <ServiceOne/>
    <Challange/>
    <Subscribe/>
    <Project/>
    <Blog/>
    <FooterTwo/>
  </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import SliderThree from "../components/HomeThree/SliderThree";
    import ServiceTwo from "../components/HomeTwo/ServiceTwo";
    import About from "../components/Home/About";
    import ServiceOne from "../components/Home/ServiceOne";
    import Challange from "../components/Home/Challange";
    import Subscribe from "../components/Home/Subscribe";
    import Project from "../components/Home/Project";
    import Blog from "../components/Home/Blog";
    import FooterTwo from "../components/HomeTwo/FooterTwo";
    export default {
        name: "index-3",
      components: {FooterTwo, Blog, Project, Subscribe, Challange, ServiceOne, About, ServiceTwo, SliderThree, HeaderTwo}
    }
</script>

<style scoped>

</style>
