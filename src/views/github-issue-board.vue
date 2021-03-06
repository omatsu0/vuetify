<template>
  <v-container class="container gray">
    <v-col cols="1" class="container2">
      <v-row class="item blue">Item 1</v-row>
      <v-row class="item red">Item 2</v-row>
      <v-row class="item indigo">Item 3</v-row>
      <v-row class="item pink">Item 4</v-row>
    </v-col>
    <v-col class="container3">
      <v-row class="orange">あああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああ</v-row>
    </v-col>
  </v-container>
</template>

<style>
.gray{
  background-color: gray;
  display: flex;
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
.inline-block{
  display: inline-block;
}
.container3{
  display: flex;
  width:inherit;
  background-color: black;
}
</style>
