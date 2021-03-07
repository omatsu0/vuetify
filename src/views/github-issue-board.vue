<template>
  <v-container class="container gray d-flex">
    <v-row class="container2 ma-0">
      <v-col class="item blue">Item 1</v-col>
      <v-col class="item red">Item 2</v-col>
      <v-col class="item indigo">Item 3</v-col>
      <v-col class="item pink">Item 4</v-col>
    </v-row>
    <v-row class="container3 ma-0">
      <v-col class="orange">あああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああ</v-col>
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
  display: flex;
  flex-direction: column;
}
.container3{
  width:inherit;
  background-color: black;
}
</style>
