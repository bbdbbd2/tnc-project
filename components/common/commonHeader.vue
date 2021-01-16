<template>
  <v-container>
    <v-row>
      <v-col>
        <v-img
          src="/logo.png"
          max-height="100px"
          max-width="100px"
          class="ml-5"
        ></v-img>
      </v-col>
      <v-col align-self="end">
        <div class="menuBtn">
          <v-btn-toggle tile color="deep-purple accent-3" group>
            <v-btn>교회소개</v-btn>
            <v-btn>설교영상</v-btn>
            <v-btn>커뮤니티</v-btn>
            <v-btn>오시는길</v-btn>
            <v-btn>CONTACT</v-btn>
          </v-btn-toggle>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<style>
.menuBtn {
  background-color: aquamarine;
  width: 450px;
  margin-left: 500px;
}
</style>
