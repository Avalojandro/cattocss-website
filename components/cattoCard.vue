<template>
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
</template>

<style>
.catto-div {background-image: linear-gradient(to right, #FF512F 0%, #ff7b2f  51%, #FF512F  100%)}
.catto-div {transition: 0.5s; background-size: 200% auto;}
.catto-div:hover {background-position: right center; /* change the direction of the change here */}

.btn-grad {background-image: linear-gradient(to right, #ff7b2f 0%, #FF512F  51%, #ff7b2f  100%)}
.btn-grad {transition: 0.5s; background-size: 200% auto; border-width: 1px;}
.btn-grad:hover {background-position: right center; /* change the direction of the change here */}
</style>