<template>
    <div>
      <HeaderTwo/>
      <PageBanner pageTitle="Service Details"/>
      <ServiceDetails/>
      <Footer/>
    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import ServiceDetails from "../components/ServiceDetails";
    import Footer from "../components/Home/Footer";
    export default {
        name: "service-details",
      components: {
          Footer,
        ServiceDetails,
        PageBanner,
        HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Service Details'
        }
      }
    }
</script>

<style scoped>

</style>
