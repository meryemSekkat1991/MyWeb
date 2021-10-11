<template>
   <div>
     <HeaderTwo/>
     <PageBanner pageTitle="Review"/>
     <TestimonialsReview/>
     <Footer/>
   </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import Footer from "../components/Home/Footer";
    import TestimonialsReview from "../components/Page/TestimonialsReview";
    export default {
        name: "review",
      components: {
        TestimonialsReview,
          Footer,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Review'
        }
      }
    }
</script>

<style scoped>

</style>
