<template>
  <div class="container gray">
    <div class="container2">
      <div class="item blue">Item 1</div>
      <div class="item red">Item 2</div>
      <div class="item indigo">Item 3</div>
      <div class="item pink">Item 4</div>
    </div>
    <div class="container3">
      <div class="orange">あああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああ</div>
    </div>
  </div>
</template>

<style>
.gray{
  background-color: gray;
  display: flex;
}
.blue{
  background-color: blue;
  white-space: nowrap;
  padding: 10px;
}
.red{
  background-color: red;
  white-space: nowrap;
  padding: 10px;
}
.indigo{
  background-color: indigo;
  white-space: nowrap;
  padding: 10px;
}
.pink{
  background-color: pink;
  white-space: nowrap;
  padding: 10px;
}
.inline-block{
  display: inline-block;
}
.container2{
  display: flex;
  flex-direction: column;

}
.container3{
  display: flex;
  width:inherit;
  background-color: black;
}
.orange{
  padding:10px;
}
</style>
