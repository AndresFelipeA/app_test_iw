<template>
  <div>
    <Navbar/>
  </div>
  <router-view/>
    <Footer />
</template>

<script>
  import Navbar from '@/components/Navbar';
  import Footer from '@/components/Footer';
export default {
  name: "App",
  components:{
    Navbar,
    Footer,
  },
}
</script>

<style>
.bg-general{

  background-color: salmon;

}
</style>
