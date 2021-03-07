<template>
  <v-container>
    <v-row justify="space-between" class="question_header">
      <v-col cols="12" md="11" order="last" order-md="first">
        <h1 class="question_title mb-2">
          VSCode のフォント設定によって太文字がずれる場合があるあああああああああああああああああああああああああああああああああああ
        </h1>
      </v-col>
      <v-spacer>
      </v-spacer>
      <v-col cols="12" md="1" order="first" order-md="last" align="end" >
        <v-btn color="secondary" class="pa-2 question_btn">質問する</v-btn>
      </v-col>
    </v-row>

    <v-row class="mt-0 question-data">
      <v-col cols="3">
        <span></span>
        <span></span>
      </v-col>
      <v-col cols="3"></v-col>
      <v-col cols="3"></v-col>
    </v-row>
  </v-container>
</template>
<style>
.question_header{
  background-color: indigo;
}
.question_title{
  word-wrap: break-word !important;
  line-height: 1.3;
  margin: 0 0 1em;
  background-color: pink;
  font-weight: normal;
  font-size:2.07692308rem;
  font-family: var(--theme-question-title-font-family);
}
.question_btn{
  font-size: inherit;
}
</style>
