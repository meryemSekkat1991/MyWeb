<template>
    <div>
      <HeaderTwo/>
      <PageBanner pageTitle="About us"/>
      <WorkProses/>
      <About/>
      <SubscribeTwo/>
      <Brand/>
      <Team/>
      <Footer/>
    </div>
</template>

<script>
    import HeaderTwo from "../components/HomeTwo/HeaderTwo";
    import Footer from "../components/Home/Footer";
    import PageBanner from "../components/Page/PageBanner";
    import About from "../components/Home/About";
    import WorkProses from "../components/Page/WorkProses";
    import SubscribeTwo from "../components/Page/SubscribeTwo";
    import Brand from "../components/Page/Brand";
    import Team from "../components/Page/Team";


    export default {
        name: "about",
      components: {
          Team,
          Brand,
          SubscribeTwo,
          WorkProses,
          About,
          PageBanner,
          Footer,
          HeaderTwo
        },
      head(){
          return{
            title: 'MyWeb | About Us'
          }
      }
    }
</script>

