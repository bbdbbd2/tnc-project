<template>
  <v-container fluid>
    <v-row class="d-flex justify-end">
      <v-col>
        <vs-button size="small" color="dark" type="flat" icon="play_arrow"
          >KR</vs-button
        >
        <vs-button size="small" color="dark" type="flat" icon="play_arrow"
          >JP</vs-button
        >
      </v-col>
    </v-row>
    <v-row justify="center" align="end">
      <v-img
        src="TNC_logo_Bcolor_white.png"
        max-height="200px"
        max-width="400px"
        class="ml-5"
      ></v-img>
    </v-row>
    <v-row class="mt-6" justify="center">
      <v-col cols="auto" align-self="end">
        <vs-button-group>
          <vs-dropdown>
            <vs-button color="dark" type="flat"> 교회소개 </vs-button>
            <vs-dropdown-menu>
              <vs-dropdown-item> option1 </vs-dropdown-item>
              <vs-dropdown-item> option2 </vs-dropdown-item>
              <vs-dropdown-item> option3 </vs-dropdown-item>
            </vs-dropdown-menu>
          </vs-dropdown>
          <vs-dropdown>
            <vs-button color="dark" type="flat"> 설교영상 </vs-button>
            <vs-dropdown-menu>
              <vs-dropdown-item> option1 </vs-dropdown-item>
              <vs-dropdown-item> option2 </vs-dropdown-item>
              <vs-dropdown-item> option3 </vs-dropdown-item>
            </vs-dropdown-menu>
          </vs-dropdown>
          <vs-dropdown>
            <vs-button color="dark" type="flat"> 공지사항 </vs-button>
            <vs-dropdown-menu>
              <vs-dropdown-item> option1 </vs-dropdown-item>
              <vs-dropdown-item> option2 </vs-dropdown-item>
              <vs-dropdown-item> option3 </vs-dropdown-item>
            </vs-dropdown-menu>
          </vs-dropdown>
          <vs-dropdown>
            <vs-button color="dark" type="flat"> 커뮤니티 </vs-button>
            <vs-dropdown-menu>
              <vs-dropdown-item> option1 </vs-dropdown-item>
              <vs-dropdown-item> option2 </vs-dropdown-item>
              <vs-dropdown-item> option3 </vs-dropdown-item>
            </vs-dropdown-menu>
          </vs-dropdown>
          <vs-dropdown>
            <vs-button color="dark" type="flat"> 오시는길 </vs-button>
            <vs-dropdown-menu>
              <vs-dropdown-item> option1 </vs-dropdown-item>
              <vs-dropdown-item> option2 </vs-dropdown-item>
              <vs-dropdown-item> option3 </vs-dropdown-item>
            </vs-dropdown-menu>
          </vs-dropdown>
          <vs-dropdown>
            <vs-button color="dark" type="flat"> CONTACT </vs-button>
            <vs-dropdown-menu>
              <vs-dropdown-item> option1 </vs-dropdown-item>
              <vs-dropdown-item> option2 </vs-dropdown-item>
              <vs-dropdown-item> option3 </vs-dropdown-item>
            </vs-dropdown-menu>
          </vs-dropdown>
        </vs-button-group>
        <!-- <v-menu open-on-hover b offset-y>
          <template v-slot:activator="{ on, attrs }">
            <v-btn
              color="white"
              v-bind="attrs"
              v-on="on"
              v-for="(item2, index) in items2"
              :key="index"
            >
              {{ item2.btnName }}
            </v-btn>
          </template>
          <v-list>
            <v-list-item v-for="(item, index) in items" :key="index">
              <v-list-item-title>{{ item.title }}</v-list-item-title>
            </v-list-item>
          </v-list>
        </v-menu> -->
        <!-- <v-btn-toggle tile color="deep-purple accent-3" group>
          <v-btn>교회소개</v-btn>
          <v-btn>설교영상</v-btn>
          <v-btn>커뮤니티</v-btn>
          <v-btn>오시는길</v-btn>
          <v-btn>CONTACT</v-btn>
        </v-btn-toggle> -->
      </v-col>
    </v-row>
    <vs-divider color="dark"></vs-divider>
  </v-container>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      items: [
        { title: 'Click Me' },
        { title: 'Click Me' },
        { title: 'Click Me' },
        { title: 'Click Me' },
      ],
      items2: [
        { btnName: '교회소개' },
        { btnName: '설교영상' },
        { btnName: '커뮤니티' },
        { btnName: '오시는길' },
        { btnName: 'CONTACT' },
      ],
    }
  },
})
</script>

<style></style>
