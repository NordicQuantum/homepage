<template>
  <div>
    <Hero />
    <Clients />
    <Vision />
    <Mission />    
    <FeaturedBlogs />   
  </div>
</template>

<script>
import Hero from "~/components/homepage/Hero"
import Clients from "~/components/homepage/Clients"
import Vision from "~/components/homepage/Vision"
import Mission from "~/components/homepage/Mission"
import FeaturedBlogs from "~/components/homepage/FeaturedBlogs"



export default {
  components: {
    Hero,
    Clients,
    Vision,    
    FeaturedBlogs,   
    Mission
  }
}
</script>