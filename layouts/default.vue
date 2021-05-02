<template>
  <div class="bg-site h-full">
    <NavHeader />
    <Nuxt />
  </div>
</template>

<style>
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


.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s;
}
.page-enter,
.page-leave-to {
  opacity: 0;
}

.layout-enter-active,
.layout-leave-active {
  transition: opacity 0.5s;
}
.layout-enter,
.layout-leave-to {
  opacity: 0;
}

.slide-bottom-enter-active,
.slide-bottom-leave-active {
  transition: opacity 0.25s ease-in-out, transform 0.25s ease-in-out;
}
.slide-bottom-enter,
.slide-bottom-leave-to {
  opacity: 0;
  transform: translate3d(0, 15px, 0);
}
.bounce-enter-active {
  transform-origin: top;
  animation: bounce-in 0.8s;
}
.bounce-leave-active {
  transform-origin: top;
  animation: bounce-out 0.5s;
}
@keyframes bounce-in {
  0% {
    transform: scale(0);
  }
  50% {
    transform: scale(1.25);
  }
  100% {
    transform: scale(1);
  }
}
@keyframes bounce-out {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.25);
  }
  100% {
    transform: scale(0);
  }
}

</style>
