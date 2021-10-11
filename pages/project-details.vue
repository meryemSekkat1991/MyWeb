<template>
  <div>
    <HeaderTwo/>
    <PageBanner pageTitle="Project Details"/>
    <ProjectDetails/>
    <Footer/>
  </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import ProjectDetails from "../components/ProjectDetails";
    import Footer from "../components/Home/Footer";
    export default {
        name: "project-details",
      components: {
          Footer,
          ProjectDetails,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Project Details'
        }
      }
    }
</script>

<style scoped>

</style>
