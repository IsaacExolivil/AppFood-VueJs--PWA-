<template>
  <div class="home">
    <div class="header">
      <h2 class="title">Hi <b>Isaac!</b></h2>
      <div class="input">
        <input type="text" placeholder="Find what you want..." />
        <div class="icon-input">
          <i class="bx bx-search"></i>
        </div>
      </div>
      <div class="combo-header">
        <div class="text">
          <h3>Free combo</h3>
          <p>Burger + Coca-cola for new users</p>
        </div>
        <div class="img">
          <img
            src="https://images.unsplash.com/photo-1565299507177-b0ac66763828?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=844&q=80"
          />
        </div>
      </div>
    </div>
    <div class="scroll-menu">
      <div class="scroll-content">
        <div :key="index" class="avatar" v-for="(item, index) in 10">
          <i class="bx bxs-pizza bx-sm"></i>
        </div>
      </div>
    </div>
   
    <div class="top-products">
       <h2>Top Product</h2>
      <div class="top-products-img">
        <img  src="https://images.unsplash.com/photo-1527661591475-527312dd65f5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=715&q=80"/>
      </div>
      
        <div class="top-products-text">
          <div class="top-products-title">Berry Juice</div>
          <div class="top-products-price">$7.50</div>

          </div>
          
            <i class="bx bx-plus-medical"></i>

            
        
    </div>
  </div>
</template>


<style lang="less">
h2 {
  font-weight: 400;
}
.home {
   
  .top-products {
  margin-top: 15px;
  
    
    .top-products-img{
      padding: 10px;
      margin-top: 15px;
      border-radius: 20px;
      
      img{
        
        width: 100%;
      }
    }
    position: relative;
    i {
      position: absolute;
      right: 0%;
      padding: 10px;
      bottom: 0%;
      color: white;
      border-radius: 50px;
      background-color: rgba(74, 174, 84);
    }
    max-width: 140px;
    
    .top-products-text {
       margin-top: 10px;
      .top-products-price{
        color: rgba(255, 131, 62);
      }
      color: rgba(47, 47, 47);
    }
  }
  margin: 20px;
  .scroll-menu {
    margin-top: 30px;
    .scroll-content {
      display: flex;
      overflow-y: auto;
      .avatar {
        background-color: rgb(250, 248, 248);
        padding: 20px;
        border-radius: 10px;
        margin: 10px;
        i {
          color: rgba(255, 131, 62);
        }
      }
    }
  }
}

.header {
  .combo-header {
    margin-top: 30px;

    background-color: rgb(255, 131, 62);
    color: white;
    padding: 20px;
    border-radius: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .img {
      width: 40%;
      img {
        width: 85%;
        object-fit: cover;
      }
    }
    .text {
      width: 50%;
      h3 {
        font-weight: 400px;
      }
      p {
        font-weight: 300px;
      }
    }
  }
  .input {
    display: flex;
    position: relative;
    align-items: center;
    margin-top: 20px;
    input {
      width: 100%;
      background-color: rgb(250, 248, 248);
      border: 0px;
      outline: none;
      padding: 10px;
      padding-left: 30px;
      border-radius: 10px;
    }
    .icon-input {
      position: absolute;
      margin-left: 10px;
    }
  }
  .title {
    font-weight: 350;
  }
}
</style>

