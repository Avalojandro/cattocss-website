<template>
        <div class="tailwind-div rounded-lg h-96 p-4">
      <span class="text-black font-poppins font-medium text-4xl">catto</span><br>
      <span class="text-white font-poppins font-medium text-4xl">softwind</span>
      <br><br>
      <span class="font-bold text-lg">
        The Catto components made with tailwind css to integrate in your tailwind projects
      </span><br>
      <button class="border-blue-400 z-20 relative btn-grad2 text-white px-4 py-2 mt-4 rounded-lg backdrop-opacity-50">Get Started</button>
    </div>
</template>

<style>
    .tailwind-div{background-image: linear-gradient(to right, #1FA2FF 0%, #12D8FA  51%, #1FA2FF  100%);}
.tailwind-div {transition: 0.5s; background-size: 200% auto;}
.tailwind-div:hover {background-position: right center; /* change the direction of the change here */}

.btn-grad2 {background-image: linear-gradient(to right, #12D8FA 0%, #1FA2FF  51%, #12D8FA  100%)}
.btn-grad2 {transition: 0.5s; background-size: 200% auto; border-width: 1px;}
.btn-grad2:hover {background-position: right center; /* change the direction of the change here */}
</style>