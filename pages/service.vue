<template>
    <div>
      <HeaderTwo/>
      <PageBanner page-title="Services"/>
      <ServiceTwo/>
      <ServiceOne/>
      <Challange/>
      <Footer/>
    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import ServiceTwo from "../components/HomeTwo/ServiceTwo";
    import ServiceOne from "../components/Home/ServiceOne";
    import Challange from "../components/Home/Challange";
    import Footer from "../components/Home/Footer";
    export default {
        name: "service",
      components: {
          Footer,
          Challange,
          ServiceOne,
          ServiceTwo,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Services'
        }
      }
    }
</script>

<style scoped>

</style>
