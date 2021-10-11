<template>
    <div>
      <HeaderTwo/>
      <PageBanner pageTitle="FAQ"/>
      <Faq/>
      <Footer/>
    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import Faq from "../components/Page/Faq";
    import Footer from "../components/Home/Footer";
    export default {
        name: "faq",
      components: {
          Footer,
          Faq,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | FAQ'
        }
      }
    }
</script>

<style scoped>

</style>
