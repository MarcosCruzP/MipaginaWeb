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
      <br />
      <div>
        <a href="https://github.com/MarcosCruzP" target="_blanck"
          ><v-btn prepend-icon="mdi-github"> </v-btn
        ></a>
      </div>
    </div>
  </div>
  <v-card>
    <div class="titulos ma-4" justify="center" align="center">Mis hablidades principales</div>
    <div class="skill">
      <div class="sep"></div>
      <v-tooltip text="Vue - Avanzado" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/vue.png" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text="Laravel - Avanzado" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/Laravel.jpg" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text="AWS - Intermedio" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/aws.jpg" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text="Docker -  Basico - Intermedio" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/docker.png" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text="Kubernates - Basico - Intermedio" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/JS.png" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text=".NET - Intermedio - AVANZADO" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/net.png" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text="Sql server - Intermedio - AVANZADO" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/sqlser.jpg" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text="Fusion 360 - Intermedio - AVANZADO" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/fus360.jpg" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text="Spressif - Intermedio - AVANZADO" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/espsif.png" alt="" />
        </template>
      </v-tooltip>

      <v-tooltip text="Flutter- Basico - Intermedio" location="bottom">
        <template v-slot:activator="{ props }">
          <img v-bind="props" src="/src/assets/Mskills/flutter.png" alt="" />
        </template>
      </v-tooltip>

      <div class="sep"></div>
    </div>
  </v-card>
  <div></div>

  <div style="background-color: #394139; height: 110vh; display: flex">
    <div class="line" style="background-color: white"></div>
    <v-card class="carddt1" variant="elevated">
      <v-row style="height: 60%">
        <img
          src="/src/assets/sobreMi.jpg"
          alt=""
          style="width: 26%; margin: 5%; border-radius: 40px"
        />
        <div class="detallesSobremi">
          <div><b>Sobre mi</b></div>
          <div class="rol">Hola, mi nombre es Marcos Cruz Pascacio</div>
          <br />
          <div>
            Desarrollador especializado en IoT (Internet de las cosas), apasionado por la
            interconexión de las cosas y crear sistemas que ayuden a facilitar, agilizar, optimizar
            procesos que entorpecen el trabajo como la eficiencia de la productividad. Cuento con 5
            años de experiencia en el desarrollo para compañías de fabricación, servicios,
            desarrollo de productos, identificación de problemas e implementación de mejoras.
            <br /><br />
            Me he desempeñado en diversas ramas del desarrollo que al especializarme en IoT me ha
            permitido adquirir los conocimientos y capacidades de desarrollo que he aplicado en las
            diversas compañías que he brindado mis servicios. Mis habilidades son:
            <br /><br />
            • Desarrollo Full Stack • Diseño de hardware • Desarrollo de Sistemas embebidos • AWS •
            Arquitectura de microservicios • Modelado 3D
          </div>
        </div> </v-row
      ><br /><br />
      <v-divider :thickness="4" color="white"></v-divider>
      <br />
      <div>
        <div class="titulos ma-4" justify="center" align="center">Los Servicios que te ofrezco</div>
        <v-row align="center" class="ma-4" justify="center">
          <div class="ma-4" justify="center" align="center">
            <v-icon size="xxx-large">mdi-code-tags</v-icon> <br /><br />
            Desarrollo de software
          </div>

          <div class="ma-4" justify="center" align="center">
            <v-icon size="xxx-large">mdi-transition</v-icon> <br /><br />
            Consultoria para la transformacion digital
          </div>

          <div class="ma-4" justify="center" align="center">
            <v-icon size="xxx-large">mdi-wifi</v-icon> <br /><br />
            Desarrollo de sistemas IOT
          </div>
        </v-row>
      </div>
    </v-card>
  </div>
  <div
    style="height: 40vh; width: 100%; color: #0000; background-color: #f2eeea; margin-top: -15px"
  >
    <br />
    <div class="titulos ma-4" justify="center" align="center" style="color: #000">
      Quienes confian en mi trabajo
    </div>
    <v-row justify="center" align="center" class="ma-4">
      <img
        style="max-width: 20%; height: 100px; object-fit: scale-down; margin-right: 2%"
        src="/src/assets/evosys.png"
        alt=""
      />
      <img
        style="max-width: 20%; height: 100px; object-fit: scale-down; margin-right: 3%"
        src="/src/assets/Can.png"
        alt=""
      />
      <img
        style="max-width: 20%; height: 100px; object-fit: scale-down; margin-right: 5%"
        src="/src/assets/eecore.png"
        alt=""
      />
      <img
        style="max-width: 20%; height: 100px; object-fit: scale-down; margin-right: 5%"
        src="/src/assets/pazzia.png"
        alt=""
      />
      <img
        style="max-width: 20%; height: 100px; object-fit: scale-down"
        src="/src/assets/cyrisrael.png"
        alt=""
      />
    </v-row>
  </div>

  <div class="proyectos" style="height: 20vh">
    <div class="line" style="background-color: white"></div>
    <div style="" class="line3"></div>
    <div style="font-size: 40px; color: white; margin-top: 3%; margin-left: 50px">
      MIS PROYECTOS
    </div>
  </div>
  <div class="proyectos2">
    <div class="line" style="background-color: white; height: auto"></div>
    <v-card class="carddt2">
      <v-card class="proyecto">
        <v-row style="width: 100%">
          <img src="/src/assets/CAN_prenent.png" alt="" style="width: 45%" />
          <div style="width: 43%; margin-left: 5%; margin-top: 6%">
            <h1>C.A.N. sistema</h1>
            <div>
              sistema administrativo para la gestión de asistencias, seguimiento de miembros y
              estudiantes con módulos de análisis de información
            </div>
            <br />
            <div style="display: flex" class="tecnologias">
              <v-tooltip text="Vue - Avanzado" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/vue.png" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="Laravel - Avanzado" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/Laravel.jpg" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="AWS - Intermedio" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/aws.jpg" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="Docker -  Basico - Intermedio" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/docker.png" alt="" />
                </template>
              </v-tooltip>
            </div>
          </div>
        </v-row>
      </v-card>

      <v-card class="proyecto">
        <v-row style="width: 100%; display: flex; flex-direction: row-reverse">
          <img
            src="/src/assets/AsistencesIOT.jpeg"
            alt=""
            style="width: 35%; object-fit: scale-down; margin-left: 2%"
          />
          <div style="width: 43%; margin-right: 5%; margin-top: 6%">
            <h1>Asistencias IOT</h1>
            <div>
              sistema administrativo para la gestión de asistencias, seguimiento de miembros y
              estudiantes con módulos de análisis de información
            </div>
            <br />
            <div style="display: flex" class="tecnologias">
              <v-tooltip text="Laravel" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/Laravel.jpg" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="AWS" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/aws.jpg" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="esspresif" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/espsif.png" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="Fusion 360" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/fus360.jpg" alt="" />
                </template>
              </v-tooltip>
              <v-tooltip text="Eagle" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/eagle.png" alt="" />
                </template>
              </v-tooltip>
            </div>
          </div>
        </v-row>
      </v-card>

      <v-card class="proyecto">
        <v-row style="width: 100%">
          <img src="/src/assets/Core.jpg" alt="" style="width: 45%" />
          <div style="width: 43%; margin-left: 5%; margin-top: 6%">
            <h1>Core Reportes de pruebas de transformadores (Plataforma)</h1>
            <div>
              sistema administrativo para la gestión de asistencias, seguimiento de miembros y
              estudiantes con módulos de análisis de información
            </div>
            <br />
            <div style="display: flex" class="tecnologias">
              <v-tooltip text="Vue - Avanzado" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/vue.png" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="Laravel - Avanzado" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/Laravel.jpg" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="AWS - Intermedio" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/aws.jpg" alt="" />
                </template>
              </v-tooltip>

              <v-tooltip text="Docker -  Basico - Intermedio" location="bottom">
                <template v-slot:activator="{ props }">
                  <img v-bind="props" src="/src/assets/Mskills/docker.png" alt="" />
                </template>
              </v-tooltip>
            </div>
          </div>
        </v-row>
      </v-card>
    </v-card>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Playwrite+IS:wght@100..400&display=swap');
.line {
  width: 1px;
  height: 100%;
  margin-left: 10%;
  background-color: black;
}
.line2 {
  width: 3px;
  margin-top: 30vh;
  height: 10vh;
  background-color: black;
}

.line3 {
  width: 3px;
  height: 40%;
  margin-top: 5vh;
  background-color: white;
}

.carddt1 {
  position: relative;
  left: -4%;
  height: 80%;
  top: 10%;
  width: 85%;
  background-color: #4c574c;
  color: white;
}

.tecnologias img {
  width: 5%;
}

.carddt2 {
  position: relative;
  left: -4%;
  top: 30%;
  width: 90%;
  background-color: transparent;
  margin-bottom: 10vh;
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

.proyectos {
  background: #4d4542;
  margin-top: -15px;
  display: flex;
}
.proyecto {
  width: 95%;
  margin-left: 2%;
  background-color: #211e1c;
  color: white;
  height: 50vh;
  margin-bottom: 60px;
}
.proyectos2 {
  background: #4d4542;
  margin-top: -15px;
  display: flex;
}

.titulos {
  font-family: 'Montserrat', sans-serif;
  font-size: 30px;
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

.skill {
  height: auto;
  width: 65%;
  margin-top: 30px;
  margin-left: 17.5%;
  padding: 30px;
  -webkit-box-shadow: 6px 10px 22px 1px rgba(166, 166, 166, 0.79);
  -moz-box-shadow: 6px 10px 22px 1px rgba(166, 166, 166, 0.79);
  box-shadow: 6px 10px 22px 1px rgba(166, 166, 166, 0.79);
  border-radius: 20px;
  flex-wrap: wrap;

  display: flex;
  justify-content: space-between;
  margin-bottom: 40px;
}

.skill img {
  width: 5%;
  height: 50px;
  border-radius: 10px;
}

.skill .sep {
  width: 5%;
}

.detallesSobremi {
  margin: 5%;
  margin-left: 0%;
  width: 50%;
  text-align: justify;
}
</style>
