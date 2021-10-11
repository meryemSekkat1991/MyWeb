<template>
    <div>
      <HeaderTwo/>
      <SliderTwo/>
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
    import HeaderTwo from "~/components/HomeTwo/HeaderTwo.vue";
    import SliderTwo from "~/components/HomeTwo/SliderTwo.vue";
    import ServiceTwo from "~/components/HomeTwo/ServiceTwo.vue";
    import About from "~/components/Home/About.vue";
    import ServiceOne from "~/components/Home/ServiceOne.vue";
    import Challange from "~/components/Home/Challange.vue";
    import Subscribe from "~/components/Home/Subscribe.vue";
    import Project from "~/components/Home/Project.vue";
    import Blog from "~/components/Home/Blog.vue";
    import FooterTwo from "~/components/HomeTwo/FooterTwo.vue";





    export default {
        name: "index-2",
      components: {
        FooterTwo,
        Blog,
        Project,
        Subscribe,
        Challange,
        ServiceOne,
        About,
        ServiceTwo,
        SliderTwo,
        HeaderTwo
      }
    }
</script>

<style scoped>

</style>
