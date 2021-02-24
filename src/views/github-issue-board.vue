<template>
  <v-container fluid mr-5>
    <v-row class="grey lighten-3" justify="space-between" style="height: 200px;">
      <v-col cols="7" alignSelf="center" style="background-color: #FFCDD2">
        <h1 :font-size="$vuetify.breakpoint.xs ? 20 : 5">タイトルタイ</h1>
      </v-col>
      <v-col style="background-color: #E1BEE7">
        <v-btn color="primary">質問する</v-btn>
        <!-- <v-btn color="primary" :min-height="$vuetify.breakpoint.xs ? 300 : '20vh'">質問する</v-btn> -->
        <!-- <v-btn :block="$vuetify.breakpoint.xsOnly" flat>Cancel</v-btn> -->
      </v-col>
    </v-row>
  </v-container>
</template>
<style scoped>
h1{
  font-size:1.5rem;
}
</style>
