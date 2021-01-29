<template>
  <v-footer dark padless :absolute="!fixed" app>
    <v-card
      width="100%"
      flat
      tile
      class="grey darken-2 white--text text-center"
    >
      <v-card-text>
        <v-btn v-for="icon in icons" :key="icon" class="mx-4 white--text" icon>
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0"
        >© COPYRIGHTS 2020 TOKYO NEW CHURCH. ALL RIGHTS RESERVED.
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text d-flex justify-center">
        <v-img
          src="TNC_logo_B_white.png"
          max-height="100px"
          max-width="100px"
        ></v-img>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script lang="ts">
export default {
  data() {
    return {
      fixed: false,
      icons: ['mdi-facebook', 'mdi-instagram'],
    }
  },
}
</script>
