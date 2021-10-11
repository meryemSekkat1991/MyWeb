<template>
    <div>
      <HeaderTwo/>
      <PageBanner pageTitle="Project-2"/>
      <ProjectTwo/>
      <Footer/>
    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import ProjectTwo from "../components/ProjectTwo";
    import Footer from "../components/Home/Footer";
    export default {
        name: "project-2",
      components: {
        Footer,
        ProjectTwo,
          PageBanner,
        HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Project-2'
        }
      }
    }
</script>

<style scoped>

</style>
