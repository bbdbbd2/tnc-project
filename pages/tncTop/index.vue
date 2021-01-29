<template>
  <v-container>
    <v-row justify="center" dense no-gutters>
      <v-col cols="auto">
        <v-carousel
          cycle
          align-items="center"
          justify-content="center"
          height="500"
          hide-delimiter-background
          show-arrows-on-hover
        >
          <v-carousel-item
            v-for="(item, i) in items"
            :key="i"
            :src="item.src"
            reverse-transition="fade-transition"
          ></v-carousel-item>
        </v-carousel>
      </v-col>
    </v-row>
    <v-spacer></v-spacer>
    <vs-divider class="mt-10" color="dark">Message & Notice</vs-divider>
    <vs-row class="mt-10" vs-justify="center">
      <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6">
        <vs-card actionable class="cardx">
          <div slot="header">
            <h3>최신설교</h3>
          </div>
          <div slot="media">
            <v-img src="img2.jpg" max-height="200px" max-width="400px"></v-img>
          </div>
          <div>
            <span>예수 그리스도를 배우자(2) - 세례요한, 회개를 외치다</span>
          </div>
          <div slot="footer">
            <vs-row vs-justify="flex-end">
              <vs-button color="warning" type="gradient">View</vs-button>
            </vs-row>
          </div>
        </vs-card>
      </vs-col>
      <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6">
        <vs-card actionable class="cardx">
          <div slot="header">
            <h3>최신공지사항</h3>
          </div>
          <div slot="media">
            <v-img src="img2.jpg" max-height="200px" max-width="400px"></v-img>
          </div>
          <div>
            <span>긴급사태기간동안 대면 비대면 예배 병행</span>
          </div>
          <div slot="footer">
            <vs-row vs-justify="flex-end">
              <vs-button color="warning" type="gradient">View</vs-button>
            </vs-row>
          </div>
        </vs-card>
      </vs-col>
    </vs-row>
    <!-- <v-row class="mt-10" justify="center" dense>
      <v-col cols="6">
        <v-card color="#f4f4f1">
          <div class="d-flex flex-no-wrap justify-space-between">
            <div>
              <v-card-title>최신설교</v-card-title>
              <v-card-subtitle>예수 그리스도를 배우자(2)</v-card-subtitle>
              <v-card-text>세례요한, 회개를 외치다</v-card-text>
              <v-card-actions>
                <v-btn class="ml-2 mt-5" outlined rounded small>보러가기</v-btn>
              </v-card-actions>
            </div>
            <v-avatar class="ma-3" size="125" tile>
              <v-img
                src="https://cdn.vuetifyjs.com/images/cards/foster.jpg"
              ></v-img>
            </v-avatar>
          </div>
        </v-card>
      </v-col>
      <v-spacer></v-spacer>
      <v-col cols="6">
        <v-card color="#f4f4f1" height="188px">
          <v-card-title>최신공지사항</v-card-title>
          <v-card-subtitle
            >긴급사태기간동안 대면 비대면 예배 병행
          </v-card-subtitle>
          <v-card-actions>
            <v-btn class="ml-2 mt-5" outlined rounded small>보러가기</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
      <v-spacer></v-spacer>
    </v-row> -->
    <vs-divider class="mt-10" color="dark">ACEESS</vs-divider>
    <v-row>
      <v-col class="mt-8 mb-10" cols="12">
        <v-card color="#f4f4f1" height="500" elevation="12">
          <v-img
            height="300px"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          ></v-img>
          <v-card-title>오시는길</v-card-title>
          <v-card-subtitle>롯뽄기역 7번출구 도보 1분</v-card-subtitle>
          <v-card-text
            >※사정에 따라 예배장소가 바뀔 수 있으니 꼭 확인해주세요</v-card-text
          >
          <v-card-actions>
            <v-btn class="ml-2 mt-5" outlined rounded small>보러가기</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts" src="./index.ts"></script>
<style lang="scss" src="./index.scss"></style>
