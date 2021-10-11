<template>
  <div>
    <HeaderTwo/>
    <PageBanner pageTitle="Blog Sidebar"/>
    <BlogSidebar/>
    <Footer/>
  </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import PageBanner from "../components/Page/PageBanner";
    import BlogSidebar from "../components/BlogSidebar";
    import Footer from "../components/Home/Footer";
    export default {
        name: "blog-sidebar",
      components: {
          Footer,
          BlogSidebar,
          PageBanner,
          HeaderTwo
        },
      head(){
        return{
          title: 'MyWeb | Blog Sidebar'
        }
      }
    }
</script>

<style scoped>

</style>
