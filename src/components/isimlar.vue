<template>
    <div class="div">
<table style="width:100%">
<thead>
 <tr>
    <th>Sr. <br> No</th>
    <th>Title</th>
    <th >Name</th>
    <th>Contact No</th>
    <th>Email</th>
                    <th>Pending Appointment</th>
                    <th>Complete Appointment</th>
                    <th>Option</th>
                </tr>
            </thead>
<tbody v-for="srt in srt1">
    <tr>
        <td>{{ srt.id }}</td>
        <td>{{ srt.title }}</td>
        <td>{{ srt.name }}</td>
        <td>1234567890</td>
        <td>neha@abc.com</td>
        <td>0</td>
        <td>0</td>
        <td  >
            <button type="button" class="btn btn-primary  btn-floating  m-auto">
  <i class="fas fa-magic"></i>
</button>
<button type="button" class="btn btn-primary  btn-floating ">
    <i class="far fa-trash-can"></i>
</button>
        </td>
    </tr>
</tbody>
</table>

<p style="padding: 25px;">  Showing 1 to 8 of 8 entries  </p>
<and2></and2>
    </div>
</template>

<script setup>
import and2 from './and2.vue'
// import axios from 'axios'
import { ref } from 'vue';










</script>

<style scoped>
.div{
    width: 98%;
    height: 100vh !important ;
}
table, th, td {
  border: 0.5px solid rgb(159, 159, 159);
}
table td {
    padding: 7.1px;
    padding-left: 10px;
}
 
</style>