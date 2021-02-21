<template>
  <v-container>
    <!-- 両端揃え -->
    <v-row class="grey lighten-3 mt-5" justify="space-between" style="height: 200px;">
      <v-col cols="3" style="background-color: #FFCDD2">
        column 1
      </v-col>
      <v-spacer />
      <!-- <v-col cols="auto" style="background-color: #F8BBD0">
        column 2 column 2 column 2 column 2
      </v-col> -->
      <v-col cols="3" style="background-color: #E1BEE7">
        column 3
      </v-col>
    </v-row>

    <!-- 右端揃え -->
    <v-row class="grey lighten-3 mt-5" justify="end" style="height: 200px;">
      <v-col cols="3" style="background-color: #FFCDD2">
        column 1
      </v-col>
      <!-- <v-spacer /> -->
      <!-- <v-col cols="auto" style="background-color: #F8BBD0">
        column 2 column 2 column 2 column 2
      </v-col> -->
      <v-col cols="3" style="background-color: #E1BEE7">
        column 3
      </v-col>
    </v-row>
  </v-container>
</template>
