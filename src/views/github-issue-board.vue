<template>
  <v-container class="container gray">
    <v-row class="container1-2 pb-0">
      <v-row class="container2 d-flex ma-0">
        <v-col class="item blue">Item 1</v-col>
        <v-col class="item red">Item 2</v-col>
        <v-col class="item indigo">Item 3</v-col>
        <v-col class="item pink">Item 4</v-col>
      </v-row>
      <v-row class="container3 ma-0">
        <v-col class="orange">あああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああ</v-col>
      </v-row>
    </v-row>

    <v-row class="pt-0 container2-2">
      <!-- <v-row class="container4 ma-0">
        <v-col class="item blue"></v-col>
        <v-col class="item red"></v-col>
      </v-row> -->
    <v-row class="ma-0 row-con">
      <v-col class="green"><span class="hidden">Item 4</span></v-col>
    </v-row>
      <v-row class="container5 ma-0">
        <v-col cols="12" class="yellow">あああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああ</v-col>
      </v-row>
    </v-row>
  </v-container>
</template>
<style>
.gray{
  background-color: gray;
}
.blue{
  background-color: blue;
  white-space: nowrap;
}
.red{
  background-color: red;
  white-space: nowrap;
}
.indigo{
  background-color: indigo;
  white-space: nowrap;
}
.pink{
  background-color: pink;
  white-space: nowrap;
}
.container2{
  flex-direction: column;
}
.container3{
  width:inherit;
  background-color: black;
}
.container4{
  flex-direction: column;
}
.container1-2{
  flex-wrap: nowrap;
}
.container2-2{
  flex-wrap: nowrap;
}
.container5{
  width:inherit;
}
.green{
  background-color: green;
  white-space: nowrap;
}
.hidden{
  visibility:hidden;
}
.row-con{
  width:1000px;
}
</style>
