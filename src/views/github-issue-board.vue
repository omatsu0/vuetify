<template>
  <v-container>
    <v-col cols="1" class="indigo">
      <v-row class="blue" justify="center" align="center">aaaa
      </v-row>
      <v-row class="red" justify="center" align="center">eeeee</v-row>
      <v-row class="pink" justify="center" align="center">uuuu</v-row>
    </v-col>
    <v-col cols="8" class="cyan inline-block"><v-col class="pt-0">e---</v-col><v-col class="pb-3">e---</v-col><v-col class="pb-1">e---</v-col></v-col>

  </v-container>
</template>

<style>
.blue{
  background-color: blue;
  width: 100px;
  height: 50px;
}
.red{
  background-color: red;
  width: 100px;
  height: 50px;
}
.indigo{
  height: 150px;
  float:left;
}
.pink{
  background-color: pink;
  width: 100px;
  text-align: center;
  justify-content: center;
  height: 50px;
}
.inline-block{
  display: inline-block;
}

</style>
