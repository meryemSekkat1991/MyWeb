<template>
  <div>
    <HeaderTwo/>
    <PageBanner pageTitle="Our Team"/>
    <TeamTwo/>
    <Footer/>
  </div>
</template>

<script>
    import PageBanner from "../components/Page/PageBanner";
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import TeamTwo from "../components/Page/TeamTwo";
    import Footer from "../components/Home/Footer";
    export default {
        name: "team",
      components: {
        Footer,
        TeamTwo,
        HeaderTwo,
        PageBanner
        },
      head(){
        return{
          title: 'MyWeb | Our Team'
        }
      }
    }
</script>

<style scoped>

</style>
