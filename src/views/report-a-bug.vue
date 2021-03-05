<template>
  <v-container fluid pa-0 mx-5 style="margin-right:50px;">
    <v-row class="grey lighten-3 mt-5" justify="space-between" no-gutters style="height: 200px;">
      <v-col cols="3" style="background-color: #FFCDD2">
        <h1>タイトルです</h1>
      </v-col>
      <v-spacer />
      <!-- colの上下中央寄せ-->
      <v-col cols="3" md="3" style="text-align: center" align-self="center">
        <!-- <v-btn class="mx-auto" color="primary">column3</v-btn> -->
      </v-col>
    </v-row>
    <v-row class="grey lighten-3" justify="end" style="height: 200px;">
      <v-col cols="3" style="background-color: #FFCDD2">
        column 1
      </v-col>
      <v-col cols="3" style="background-color: #E1BEE7">
        column 3
      </v-col>
    </v-row>
    <v-row>
      <v-col md="11" style="background-color: #E1BEE7">
        aaaa
      </v-col>
    </v-row>
    <v-row>
      <v-col md="11" style="background-color: #FFCDD2">
      bbbb
      </v-col>
    </v-row>

  </v-container>
</template>

<style scoped>

h1{
  white-space: nowrap;
}
</style>
