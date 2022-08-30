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
      <div class="combo-header">
          <h3>Free combo</h3>
          <p> Burger + Coca-cola for new users</p>
        </div>
    
    </div>
  </div>
</template>


<style lang="less">
.home{
  margin: 20px;
}

.header {
  .combo-header{
    
    background-color: rgb(255, 131, 62);
    color: white;
    padding: 10px;
  }
  .input{
    display: flex;
    position: relative;
    align-items: center;
    margin-top: 20px;
    input{
      
      width: 100%;
      background-color: rgb(250, 248, 248);
      border: 0px;
      outline: none;
      padding: 10px;
      padding-left: 30px;
      border-radius: 10px;
    }
    .icon-input{
      position: absolute;
      margin-left: 10px;
    }
  }
  .title{
  font-weight: 350;
}
}
</style>

