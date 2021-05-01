<template>
    <div class="animations-div rounded-lg h-96 p-4">
      <span class="text-black font-poppins font-medium text-4xl">catto</span><br>
      <span class="text-white font-poppins font-medium text-4xl">animations</span>
      <br><br>
      <span class="font-bold text-lg">
       The classic fast and easy to use css animation library for all your projects
      </span><br>
      <button class="border-red-500 z-20 relative btn-grad3 text-white px-4 py-2 mt-4 rounded-lg backdrop-opacity-50">Get Started</button>
    </div>
</template>

<style>
    .animations-div{background-image: linear-gradient(to right, #ff0053 0%, #f06794  51%, #ff0053  100%);}
.animations-div {transition: 0.5s; background-size: 200% auto;}
.animations-div:hover {background-position: right center; /* change the direction of the change here */}

.btn-grad3 {background-image: linear-gradient(to right, #f06794 0%, #f13d79  51%, #f06794  100%)}
.btn-grad3 {transition: 0.5s; background-size: 200% auto; border-width: 1px;}
.btn-grad3:hover {background-position: right center; /* change the direction of the change here */}        
</style>

<script>
