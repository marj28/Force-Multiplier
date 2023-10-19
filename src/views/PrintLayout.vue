<template>
  <div>
    <div class="ma-4 row">
      <v-row no-gutters>
        <v-col>
          <v-container class="background-container">
            <div class="association1">Association 1</div>
            <div class="id1"></div>
            <div class="license1"></div>
            <div class="control1">Control No. 1</div>
            <div class="name1">Fullname 1</div>
            <div class="contact1">Contact No. 1</div>
            <div class="plate1">Plate No. 1</div>
            <div class="city1">City Plate No. 1</div>
          </v-container>
        </v-col>
        <v-col>
          <v-container class="background-container ml-4">
            <div class="association2">Association 2</div>
            <div class="id2"></div>
            <div class="license2"></div>
            <div class="control2">Control No. 2</div>
            <div class="name2">Fullname 2</div>
            <div class="contact2">Contact No. 2</div>
            <div class="plate2">Plate No. 2</div>
            <div class="city2">City Plate No. 2</div>
          </v-container>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script setup></script>
<style>
.license1 {
  width: 30%;
  height: 32%;
  margin: 1%;
  position: absolute;
  top: 25%;
  left: 8%;
  transform: translate(30%, 44%);
  background-image: url("@/assets/license.png");
  background-size: cover;
  background-repeat: no-repeat;
}
.license2 {
  width: 30%;
  height: 32%;
  margin: 1%;
  position: absolute;
  top: 25%;
  left: 10%;
  transform: translate(190%, 44%);
  background-image: url("@/assets/license.png");
  background-size: cover;
  background-repeat: no-repeat;
}
.association1 {
  position: absolute;
  top: 26%;
  left: 30%;
  transform: translate(-50%, -80%);
  color: black !important;
  font-size: 24px !important;
}
.association2 {
  position: absolute;
  top: 26%;
  left: 80%;
  transform: translate(-50%, -80%);
  color: black !important;
  font-size: 24px !important;
}
.id1 {
  width: 14%;
  height: 25%;
  margin: 1%;
  position: absolute;
  top: 63%;
  left: 8.5%;
  transform: translate(-50%, -80%);
  background-image: url("@/assets/images.png");
  background-size: cover;
  background-repeat: no-repeat;
}
.id2 {
  width: 14%; /* Adjust as needed to fit 2x2 grid */
  height: 25%; /* Adjust as needed to fit 2x2 grid */
  margin: 1%;
  position: absolute;
  top: 63%;
  left: 37.5%;
  transform: translate(100%, -80%);
  background-image: url("@/assets/images.png");
  background-size: cover;
  background-repeat: no-repeat;
}
.control1 {
  position: absolute;
  top: 42%;
  left: 30%;
  transform: translate(-50%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.control2 {
  position: absolute;
  top: 42%;
  left: 38%;
  transform: translate(500%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.name1 {
  position: absolute;
  top: 47%;
  left: 30%;
  transform: translate(-50%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.name2 {
  position: absolute;
  top: 47%;
  left: 45%;
  transform: translate(500%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.contact1 {
  position: absolute;
  top: 51.5%;
  left: 30%;
  transform: translate(-50%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.contact2 {
  position: absolute;
  top: 51.5%;
  left: 36%;
  transform: translate(500%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.plate1 {
  position: absolute;
  top: 58%;
  left: 13%;
  transform: translate(-50%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.plate2 {
  position: absolute;
  top: 58%;
  left: 28%;
  transform: translate(500%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.city1 {
  position: absolute;
  top: 58%;
  left: 37%;
  transform: translate(-50%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.city2 {
  position: absolute;
  top: 58%;
  left: 39%;
  transform: translate(500%, 1000%);
  color: black !important;
  font-size: 24px !important;
}
.background-container {
  background-image: url("@/assets/image.png");
  background-size: cover;
  background-repeat: no-repeat;
  height: 4000%;
}
@page {
  size: 8.5in 11in landscape;
}

/* Printing */
@media print {
  .city1 {
    position: absolute;
    top: 40%;
    left: 38%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 20px !important;
  }
  .city2 {
    position: absolute;
    top: 40%;
    left: 34%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 20px !important;
  }
  .plate1 {
    position: absolute;
    top: 40%;
    left: 13%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 20px !important;
  }
  .plate2 {
    position: absolute;
    top: 40%;
    left: 25%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 20px !important;
  }
  .contact1 {
    position: absolute;
    top: 35%;
    left: 30%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 20px !important;
  }
  .contact2 {
    position: absolute;
    top: 35%;
    left: 31%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 20px !important;
  }
  .name1 {
    position: absolute;
    top: 32%;
    left: 30%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 20px !important;
  }
  .name2 {
    position: absolute;
    top: 32%;
    left: 40%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 20px !important;
  }
  .control1 {
    position: absolute;
    top: 44%;
    left: 30%;
    transform: translate(-50%, 450%);
    color: black !important;
    font-size: 20px !important;
  }
  .control2 {
    position: absolute;
    top: 44%;
    left: 33%;
    transform: translate(500%, 450%);
    color: black !important;
    font-size: 20px !important;
  }
  .license1 {
    width: 29%;
    height: 23%;
    margin: 1%;
    position: absolute;
    top: 27.5%;
    left: 7.5%;
    transform: translate(35%, 10%);
    background-image: url("@/assets/license.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .license2 {
    width: 29%;
    height: 23%;
    margin: 1%;
    position: absolute;
    top: 27.5%;
    left: 12.5%;
    transform: translate(190%, 10%);
    background-image: url("@/assets/license.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .id2 {
    width: 14%;
    height: 18%;
    margin: 1%;
    position: absolute;
    top: 47%;
    left: 37.5%;
    transform: translate(100%, -80%);
    background-image: url("@/assets/images.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .id1 {
    width: 14%;
    height: 18%;
    margin: 1%;
    position: absolute;
    top: 47%;
    left: 8.5%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/images.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .association1 {
    position: absolute;
    top: 20%;
    left: 30%;
    transform: translate(-50%, -80%);
    color: black !important;
    font-size: 20px !important;
  }
  .association2 {
    position: absolute;
    top: 20%;
    left: 80%;
    transform: translate(-50%, -80%);
    color: black !important;
    font-size: 20px !important;
  }
  .association {
    margin-top: 20%;
    margin-left: 50%;
  }
  .background-container {
    background-image: url("@/assets/image.png");
    background-size: cover;
    background-repeat: no-repeat;
    height: 3000%;
  }
  @page {
    size: 8.5in 11in landscape;

  }

  #print-area {
    size: 100%;
    margin: 0.22 0.31 0.96 0.31 !important;
  }
}
</style>
