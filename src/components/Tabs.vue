<template>
  <div>
    <v-app>
      <v-app-bar 
      app
      absolute
      color="#6A76AB"
      dark
      shrink-on-scroll
      prominent
      src="https://picsum.photos/1920/1080?random"
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
        </v-tabs>
      </template>
      
      </v-app-bar>

      <v-content>
        <v-container fluid> 

        </v-container>
      </v-content>

      <v-footer app> </v-footer>
    </v-app>
  </div>
</template>

<script>
export default {
  props: {},
  data: () => ({}),
  created() {}
};
</script>

<style></style>
