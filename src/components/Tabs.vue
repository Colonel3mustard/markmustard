<template>
  <div>
    <v-app-bar
      app
      absolute
      color="#6A76AB"
      dark
      shrink-on-scroll
      prominent
      src="..\assets\work-stations-plus-espresso.jpg"
      fade-img-on-scroll
      scroll-target="#scrolling-techniques-3"
    >
      <template v-slot:img="{ props }">
        <v-img
          v-bind="props"
          gradient="to top right, rgba(100,115,201,.7), rgba(25,32,72,.7)"
        ></v-img>
      </template>

      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Mark Mustard</v-toolbar-title>

      <v-spacer></v-spacer>

      <template v-slot:extension>
        <v-tabs align-with-title>
          <v-tab>Skills and Tools</v-tab>
          <v-tab>Experience</v-tab>
          <v-tab>Hobbies and Interests</v-tab>
          <v-tab-item>
            <Skills />
          </v-tab-item>
          <v-tab-item>
            <Experience /> 
            </v-tab-item>
          <v-tab-item>
            <Hobbies />
          </v-tab-item>
        </v-tabs>
      </template>
    </v-app-bar>
  </div>
</template>

<script>
import Skills from "@/components/Skills.vue";
import Experience from "@/components/Experience.vue";
import Hobbies from "@/components/Hobbies.vue";

export default {
  components: {
    Skills,
    Experience,
    Hobbies
  },
  data() {
    return {};
  }
};
</script>

<style></style>
