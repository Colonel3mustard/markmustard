<template>
  <v-container fluid class="home">
    <Tabs />
    
  </v-container>
</template>

<script>
// @ is an alias to /src
import Tabs from '@/components/Tabs.vue'
// import Skills from "@/components/Skills.vue";
// import Experience from "@/components/Experience.vue";
// import Hobbies from "@/components/Hobbies.vue";

export default {
  name: 'home',
  components: {
    Tabs,
    // Skills,
    // Experience,
    // Hobbies
  }
}
</script>

<style scoped>
.home {
  background-color: rgb(20,20,20)
}
</style>
