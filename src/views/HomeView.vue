<template>
  <div class="home">
    <div  class="header">
     <h2 class="title"> Hi <b>Isaac!</b></h2>
     <div class="input">
       <input type="text" placeholder="Find what you want...">
       <div class="icon-input">
        <i class="bx bx-search"></i>
     </div>
    
     </div>
    
    </div>
  </div>
</template>


<style lang="less">
.home{
  margin: 20px;
}

.header {
  .input{
    width: 100%;
    input{
      width: 100%;
      background-color: rgb(250, 248, 248);
      border: 0px;
      outline: none;
      padding: 10px;
    }
  }
  .title{
  font-weight: 350;
}
}
</style>

