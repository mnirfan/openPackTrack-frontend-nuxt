<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <v-card>
        <v-card-title class="headline">Welcome to the PackTrack</v-card-title>
        <v-card-text>
          <p>Packing and Tracking System</p>
          <div class="text-xs-center">
            <logo/>
          </div>
        </v-card-text>
        <v-card-actions>
          <v-spacer/>
          <v-btn color="primary" 
                 flat 
                 nuxt 
                 to="/login">Masuk Sistem</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue';

export default {
  components: {
    Logo,
  },
};
</script>
