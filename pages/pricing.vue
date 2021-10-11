<template>
    <div>
      <HeaderTwo/>
      <PageBanner pageTitle="Our Pricing"/>
      <Prices/>
      <Footer/>
    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import Footer from "../components/Home/Footer";
    import Prices from "../components/Page/Prices";
    export default {
        name: "pricing",
      components: {
          Prices,
          Footer,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Our Pricing'
        }
      }
    }

</script>

<style scoped>

</style>
