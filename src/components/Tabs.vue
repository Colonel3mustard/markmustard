<template>
<div>
    <v-app-bar
      app
      fixed
      color="rgba(50, 50, 50, 1)"
      dark
      shrink-on-scroll
      prominent
      src="..\assets\work-stations-plus-espresso.jpg"
      fade-img-on-scroll
    >
      <template v-slot:img="{ props }">
        <v-img v-bind="props" gradient="to top right, rgba(50, 50, 50, .7), rgba(50, 50, 50, .7)"></v-img>
      </template>

      <v-app-bar-nav-icon v-show="false"></v-app-bar-nav-icon>

      <v-toolbar-title id="mark">Mark Mustard</v-toolbar-title>
      
      <v-spacer></v-spacer>

      <template v-slot:extension>
        <v-tabs align-with-title v-model="tab">
          <v-tab class="tabTitle">Skills</v-tab>
          <v-tab class="tabTitle">Experience</v-tab>
          <v-tab class="tabTitle">Hobbies</v-tab>
        </v-tabs>
      </template>
    </v-app-bar>
    <v-content >
    <v-tabs-items v-model="tab" >
      <v-tab-item>
        <Skills />
      </v-tab-item>
      <v-tab-item>
        <Experience />
      </v-tab-item>
      <v-tab-item>
        <Hobbies />
      </v-tab-item>
    </v-tabs-items>
    </v-content>
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
    return {
      tab: null
    };
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Permanent+Marker|Raleway&display=swap");

#mark {
  font-family: "Permanent Marker", cursive;
  font-size: 1.5em;
  padding-bottom: unset;
}
.tabs {
  font-family: "Raleway", sans-serif;
}

</style>
