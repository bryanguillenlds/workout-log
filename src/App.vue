<template>
  <div class="min-h-full font-Poppins box-border">
    <Navigation />
    <router-view />
  </div>
</template>

<script>
import Navigation from "@/components/Navigation.vue";

export default {
  components: {
    Navigation
  },

  setup() {
    // Create data / vars

    // Check to see if user is already logged in

    // If user does not exist, need to make app ready

    // Runs when there is a auth state change
    // if user is logged in, this will fire

    return {};
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700&display=swap");
</style>
