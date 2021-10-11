<template>
    <div>
      <HeaderTwo/>
      <PageBanner pageTitle="Project"/>
      <ProjectOne/>
      <Footer/>
    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import ProjectOne from "../components/ProjectOne";
    import Footer from "../components/Home/Footer";
    export default {
        name: "project",
      components: {
          Footer,
          ProjectOne,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Project'
        }
      }
    }
</script>

<style scoped>

</style>
