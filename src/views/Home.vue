<template>
  <v-app>
    <Tabs />
  </v-app>
</template>

<script>
// @ is an alias to /src
import Tabs from '@/components/Tabs.vue'
export default {
  name: 'home',
  components: {
    Tabs,
  }
}
</script>
