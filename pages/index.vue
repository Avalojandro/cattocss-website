<template>
<div class="bg-site h-full">
  <div class="py-5 mx-10 border-b items-center grid grid-cols-2">
    <div>
      <i class='bx bxl-opera bx-md transform translate-y-1  text-primary'></i>
      <span class="text-primary font-poppins font-medium text-4xl">catto</span>
      <span class="text-white font-poppins font-medium text-4xl">css</span>
    </div>
    <div class="text-right">
      <span class="text-white">
          <i class='bx bxl-github bx-sm bx-tada-hover'></i>
      </span>
    </div>
  </div>


  <div class="text-white mx-10 pt-10 font-bold text-3xl">
    Fully CSS UI components and animations to integrate into any website. 
  </div>

  <div class="grid grid-cols-1 lg:grid-cols-3 2xl:grid-cols-1 pt-10 gap-x-10 gap-y-10 px-10">
    <div class="catto-div rounded-lg h-96 p-4 overflow-hidden">
      <span class="text-black font-poppins font-medium text-4xl">catto</span><br>
      <span class="text-white font-poppins font-medium text-4xl">components</span>
      <br><br>
      <span class="font-bold text-lg">
        A 100% css component library to implement on your website, without frameworks or javascript
      </span><br>
      <button class="border-red-400 z-20 relative btn-grad text-white px-4 py-2 mt-4 rounded-lg backdrop-opacity-50">Get Started</button>
      <div class="align-right relative transform translate-x-14 -translate-y-12">
        <img src="/cattoLogo.png" class="h-52" alt="">
      </div>
    </div>
    
    <div class="tailwind-div rounded-lg h-96 p-4">
      <span class="text-black font-poppins font-medium text-4xl">catto</span><br>
      <span class="text-white font-poppins font-medium text-4xl">softwind</span>
      <br><br>
      <span class="font-bold text-lg">
        The Catto components made with tailwind css to integrate in your tailwind projects
      </span><br>
      <button class="border-blue-400 z-20 relative btn-grad2 text-white px-4 py-2 mt-4 rounded-lg backdrop-opacity-50">Get Started</button>
    </div>
    
    <div class="animations-div rounded-lg h-96 p-4">
      <span class="text-black font-poppins font-medium text-4xl">catto</span><br>
      <span class="text-white font-poppins font-medium text-4xl">animations</span>
      <br><br>
      <span class="font-bold text-lg">
       The classic fast and easy to use css animation library for all your projects
      </span><br>
      <button class="border-red-500 z-20 relative btn-grad3 text-white px-4 py-2 mt-4 rounded-lg backdrop-opacity-50">Get Started</button>
    </div>
  </div>
  
  <div class="py-1 pb-10 mt-8 mb-10 mx-10">
    <div class="font-semibold text-xl text-center font-poppins">
      <span class="text-gray-400">A project by </span>
      <span class="text-primary">Avalojandro</span>
    </div>
  </div>

</div>
</template>

<style>
/* .catto-div{
  background: rgb(251,182,43);
  background: linear-gradient(120deg, rgba(251,182,43,1) 0%, rgba(251,133,43,1) 50%, rgba(251,84,43,1) 100%);
} */
.catto-div {background-image: linear-gradient(to right, #FF512F 0%, #ff7b2f  51%, #FF512F  100%)}
.catto-div {transition: 0.5s; background-size: 200% auto;}
.catto-div:hover {background-position: right center; /* change the direction of the change here */}


.tailwind-div{background-image: linear-gradient(to right, #1FA2FF 0%, #12D8FA  51%, #1FA2FF  100%);}
.tailwind-div {transition: 0.5s; background-size: 200% auto;}
.tailwind-div:hover {background-position: right center; /* change the direction of the change here */}
/* 
.animations-div{
  background: rgb(255,69,130);
  background: linear-gradient(120deg, #ff4582 0%, #ff0053 50%, #b3003a 100%);
} */
.animations-div{background-image: linear-gradient(to right, #ff0053 0%, #f06794  51%, #ff0053  100%);}
.animations-div {transition: 0.5s; background-size: 200% auto;}
.animations-div:hover {background-position: right center; /* change the direction of the change here */}

.btn-grad {background-image: linear-gradient(to right, #ff7b2f 0%, #FF512F  51%, #ff7b2f  100%)}
.btn-grad {transition: 0.5s; background-size: 200% auto; border-width: 1px;}
.btn-grad:hover {background-position: right center; /* change the direction of the change here */}

.btn-grad2 {background-image: linear-gradient(to right, #12D8FA 0%, #1FA2FF  51%, #12D8FA  100%)}
.btn-grad2 {transition: 0.5s; background-size: 200% auto; border-width: 1px;}
.btn-grad2:hover {background-position: right center; /* change the direction of the change here */}
        
.btn-grad3 {background-image: linear-gradient(to right, #f06794 0%, #f13d79  51%, #f06794  100%)}
.btn-grad3 {transition: 0.5s; background-size: 200% auto; border-width: 1px;}
.btn-grad3:hover {background-position: right center; /* change the direction of the change here */}        





.align-left{
    text-align: left;
    text-align: -webkit-left;
    text-align: -moz-left;
    text-align: -o-left;
    text-align: -ms-left;
    text-align: -khtml-left;
}
.align-right{
    text-align: right;
    text-align: -webkit-right;
    text-align: -moz-right;
    text-align: -o-right;
    text-align: -ms-right;
    text-align: -khtml-right;
}
.align-center{
    text-align: center;
    text-align: -webkit-center;
    text-align: -moz-center;
    text-align: -o-center;
    text-align: -ms-center;
    text-align: -khtml-center;
}

</style>