<template>
    <div>
      <HeaderTwo/>
      <PageBanner pageTitle="Blog Details"/>
      <BlogDetails/>
      <Footer/>
    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import BlogDetails from "../components/BlogDetails";
    import Footer from "../components/Home/Footer";
    export default {
        name: "blog-details",
      components: {
          Footer,
          BlogDetails,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Blog Details'
        }
      }
    }
</script>

<style scoped>

</style>
