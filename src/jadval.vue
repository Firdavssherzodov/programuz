<template>
    <div class="div shadow-6">
 

<button type="button" class="btn btn-primary">
    <i class="fas fa-plus" ></i>
    Button</button>
    <search/>
    <ism/>
    </div>
 
</template>

<script setup>
import search from  './components/search.vue'
import ism from './components/isimlar.vue'
</script>


<style  scoped>
.div{
    width: 90%;
    height: 120vh;
    margin: auto;
    margin-top: 10vh;
}

.h3{
   
    color:#495057 ;
    margin-left: 11vh;
    margin-top: 5vh;
    font-weight: 300;
}
button{
    width: 25vh;   
    height: 6vh;
    margin-left:2vh ;
    margin-top: 5vh;
}
button:hover{
     background-color: rgb(28, 132, 250);
}
</style>