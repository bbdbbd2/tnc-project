<template>
  <v-app white>
    <common-header></common-header>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <common-footer></common-footer>
  </v-app>
</template>

<script>
import CommonHeader from '~/components/common/commonHeader.vue'
import CommonFooter from '~/components/common/commonFooter.vue'

export default {
  components: {
    CommonHeader,
    CommonFooter,
  },
  data() {
    return {}
  },
}
</script>

<style>
* {
  font-family: 'Nanum Gothic Coding', monospace;
}
</style>
