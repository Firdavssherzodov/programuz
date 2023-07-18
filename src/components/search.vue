<template>
    <div class="div2">
 <div class="v2">
    <p class="p11">Show</p>
    <input type="number" placeholder="10" class="form-control" id="datatable-search-input">
    <p class="p22">entries</p>
 </div>

<div class="vv2">
    <p class="qpq1">search :</p>
<input class="inpt" type="search">
</div>


    </div>
</template>

<script setup>
 
 
</script>

<style scoped>
.div2{
    width: 100%;
     height: 10vh;
   
}
.v2{
    width: 22vh;
    height: 10vh;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-left: 3vh;
}
input{
    width: 10vh;
    border: solid grey 1.5px;
    border-radius: 5px;
}
.p11{
        padding-top: 2vh;
}
.p22{
        padding-top: 2vh;
}
.vv2{
    width: 22vh;
    height: 10vh;
    margin-left: 85%;
    margin-top: -15vh;
}
.inpt{
width: 20vh;
}
 

</style>