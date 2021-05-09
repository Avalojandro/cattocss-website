<template>
<div class="h-screen">

    <div class="grid grid-cols-2 lg:grid-cols-12 mx-10">
        <div class="text-white grid grid-cols-1 col-span-2 pt-5 font-poppins">
            <compList />
        </div>


        <div class="text-white col-span-10 py-5">
            <div><buttons/></div>
            
        
        </div>

    </div>

</div>
</template>

<script>
import compList from "../components/Catto/componentsList/compList";
import alerts from "../components/Catto/alerts";
import badges from "../components/Catto/badges";
import breadcrumb from "../components/Catto/breadcrumb";
import buttonGroup from "../components/Catto/buttonGroup";
import buttons from "../components/Catto/buttons";
import cards from "../components/Catto/cards";
import emphasis from "../components/Catto/emphasis";
import forms from "../components/Catto/forms";
import list from "../components/Catto/list";
import modal from "../components/Catto/modal";
import navbar from "../components/Catto/navbar";
import progressBar from "../components/Catto/progressBar";
import select from "../components/Catto/select";


export default {

    transition: 'slide-bottom',

    components:{
        compList,
        alerts,
        badges,
        breadcrumb,
        buttonGroup,
        buttons,
        cards,
        emphasis,
        forms,
        list,
        modal,
        navbar,
        progressBar,
        select
    }
}
</script>