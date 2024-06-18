<template>
  <!-- <v-row style="">
    <div style="" class="line"></div>
    dfsdf</v-row
  > -->
  <div style="display: flex; height: 94vh; width: 100%; color: #0000; background-color: #f2eeea">
    <div style="" class="line"></div>
    <div style="" class="line2"></div>
    <div class="presentacion">
      <div class="name"><b>Marcos Cruz Pascacio</b></div>
      <div class="rol">Desarrollador IoT</div>
      <div class="detailp">
        Dogitalizar, automatizar y optimizar procesos mediante la digitalizacion e IOT es lo que
        hago.
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Playwrite+IS:wght@100..400&display=swap');
.line {
  width: 1px;
  height: 100%;

  background-color: black;
}
.line2 {
  width: 3px;
  margin-top: 30vh;
  height: 10vh;
  background-color: black;
}

.presentacion {
  margin-right: 10%;
  color: black;
  font-size: medium;
  width: 30%;
  height: 40vh;
  display: flex;
  flex-direction: column;
  margin-top: 30vh;
  margin-left: 5%;
}
.name {
  font-family: 'Montserrat', sans-serif;
  font-size: 42px;
}
.rol {
  margin-top: 10px;
  font-family: 'Playwrite IS', cursive;
  font-size: medium;
}

.detailp {
  margin-top: 15px;
  width: 55%;
  font-size: 19px;
}
</style>
