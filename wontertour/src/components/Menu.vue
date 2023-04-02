<template>
<div class="menu" >
  <div class="tour"><img width="25px" height="25px" style="margin-top: 25%; margin-left: 25%;" src="https://img.icons8.com/material-outlined/1x/airport.png"><p class="p4">Flight</p></div>
  <div class="tour"><img width="25px" height="25px" style="margin-top: 25%; margin-left: 25%;" src="https://img.icons8.com/external-linector-lineal-linector/256/external-hotel-hotel-service-linector-lineal-linector.png"><p class="p4" > Hotels</p></div>
  <div class="tour"><img width="25px" height="25px" style="margin-top: 25%; margin-left: 15%;" src="https://img.icons8.com/external-icongeek26-outline-icongeek26/256/external-cruise-transportation-icongeek26-outline-icongeek26.png"><p class="p4" > Cruises</p></div>
</div>
<div class="menu1"></div>


</template>
<script>
export default{

}
</script>
<style scoped>
.tour{
display: flex;
width: 120px;
height: 60px;
background-color:rgba(240, 248, 255, 0.848);
margin: 0;
margin-right: 4px;
}

.tour:hover{
  /* margin-top: 10%; */
/* width:200px; */

/* font-size: 12px; */
background-color:rgba(255, 255, 255, 0.534);
}
.menu{
  display: flex;
  margin-top: 10%;
}
.menu1{
width: 100%;
height: 100px;
background-color:rgba(240, 248, 255, 0.822);
}
.p4{
  margin:0; 
  margin-top: 24%;
  line-height: 2;
}
</style>