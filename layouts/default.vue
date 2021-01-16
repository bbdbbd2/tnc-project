<template>
  <v-app white>
    <common-header></common-header>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
import CommonHeader from '~/components/common/commonHeader.vue'

export default {
  components: {
    CommonHeader,
  },
  data() {
    return {

      fixed: false,

    }
  },
}
</script>
