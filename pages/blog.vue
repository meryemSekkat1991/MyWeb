<template>
    <div>
      <HeaderTwo/>
      <PageBanner pageTitle="Blog Grid"/>
      <BlogGrid/>
      <Footer/>

    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import BlogGrid from "../components/BlogGrid";
    import Footer from "../components/Home/Footer";
    export default {
        name: "blog",
      components: {
          Footer,
          BlogGrid,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb |Blog Grid'
        }
      }
    }
</script>

<style scoped>

</style>
