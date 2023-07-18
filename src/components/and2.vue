<template>
    <div class="diiv">
<div class="d1 rounded-2">First</div>
<div class="d2 rounded-2">Program</div>
<div class="d3 rounded-2">1</div>
<div class="d4 rounded-2">Next</div>
<div class="d5 rounded-2">Last</div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.diiv{
    width: 35vh;
    height: 5vh;
    display: flex;
    font-size: 13px;
    margin-left: 80%;
    margin-top: -8vh;
}
.d1{
width: 7vh;
height: 100%;
border: solid grey 1px; 
 padding: 10px;
 color: grey;
}
.d2{
width: 9vh;
height: 100%;
border: solid grey 1px;
padding: 10px;
color: grey;
}
.d3{
width: 5vh;
color: #fff;
background-color: rgba(0, 0, 255, 0.888);
height: 100%;
font-size: 25px;
 padding-left: 10px;
border: solid rgba(0, 0, 255, 0.888) 1px;
}
.d4{
width: 9vh;
height: 100%;
border: solid grey 1px;
padding: 10px;
color: grey;
}
.d5{
width: 9vh;
height: 100%;
border: solid grey 1px;
padding: 10px;
color: grey;
}




</style>