<template>
    <div>
        <h1 class="font-bold text-4xl">Buttons</h1>
            <p class="py-3">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Veritatis soluta quibusdam debitis, dicta deserunt ab quaerat corporis, optio ratione esse ut, itaque maxime quae inventore consectetur. Nulla accusamus debitis ratione.</p>
            
            <h1 class="font-bold text-2xl">Link Buttons</h1>
            <p class="my-3">Los Link Buttons son creados con la etiqueta a y funcionan para crear enlaces personalizados como botones</p>
            <h1 class="font-semibold text-xl text-primary">Link Buttons Rounded</h1>
            <a class="rounded-button basic" href="">Button A</a>
            <a class="rounded-button success" href="">Button B</a>
            <a class="rounded-button danger" href="">Button C</a>
            <a class="rounded-button warning" href="">Button D</a>
                <h1 class="font-semibold text-xl text-primary">Link Buttons Sharp</h1>
            <a class="sharp-button basic" href="">Button F</a>
            <a class="sharp-button success" href="">Button G</a>
            <a class="sharp-button danger" href="">Button H</a>
            <a class="sharp-button warning" href="">Button I</a>      
                <iframe class="rounded-md py-3" width="100%" height="300" src="//jsfiddle.net/avalojandro/n13r67Lp/3/embedded/html,css/dark/" allowfullscreen="allowfullscreen" allowpaymentrequest frameborder="0"></iframe>
            <h1 class="font-semibold text-xl text-primary">Classic Buttons</h1>
    </div>
</template>

<style>
.basic{
    background-color: #eeeeee;
    color: #424242;
    border-style: solid;
    border-width: 0.5px;
    border-color: rgb(116, 116, 116);
    color: black;
}
.success{
    background-color: #19ca09;
    border-style: solid;
    border-width: 0.5px;
    border-color: rgb(23, 199, 0);
    color: rgb(255, 255, 255);
}
.danger{
    background-color: #cc0000;
    border-style: solid;
    border-width: 0.5px;
    border-color: rgb(192, 0, 0);
    color: rgb(255, 255, 255);
}
.warning{
    background-color: #fbff00;
    border-style: solid;
    border-width: 0.5px;
    border-color: rgb(199, 202, 0);
    color: black;
}

.rounded-button{
    padding: 8px;
    display: inline-block;
    margin: 5px;
    border-radius: 5px;
}

.sharp-button{
    padding: 8px;
    display: inline-block;
    margin: 5px;
}
</style>