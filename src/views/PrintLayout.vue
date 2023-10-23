<template>
  <div>
    <div class="ma-4 row">
      <v-row no-gutters>
        <v-col>
          <v-container class="background-container">
            <div class="association1">Association 1</div>
            <div class="id1"></div>
            <div class="license1"></div>
            <div class="qr1"></div>
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
            <div class="qr2"></div>
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
/* .license1 {
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
} */
/* .association1 {
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
} */
/* .id1 {
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
  width: 14%;
  height: 25%;
  margin: 1%;
  position: absolute;
  top: 63%;
  left: 37.5%;
  transform: translate(100%, -80%);
  background-image: url("@/assets/images.png");
  background-size: cover;
  background-repeat: no-repeat;
} */
/* .control1 {
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
} */
/* .name1 {
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
} */
/* .contact1 {
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
} */
/* .plate1 {
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
} */
/* .city1 {
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
} */
.background-container {
  background-image: url("@/assets/bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  height: 4000%;
}
@page {
  size: 8.5in 11in landscape;
}

/* small screen */
/* @media (max-width: 768px) {
  .id1 {
    width: 14%;
    height: 25%;
    margin: 1%;
    position: absolute;
    top: 65% ;
    left: 8.5%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/images.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
} */

/* medium screen */
/* @media (min-width: 769px) and (max-width: 1024px) {
  .id1 {
    width: 14%;
    height: 25%;
    margin: 1%;
    position: absolute;
    top: 65% ;
    left: 8.5%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/images.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
} */

/* large screen */
@media (min-width: 1025px) and (max-width: 1440px) {
  .control1 {
    position: absolute;
    top: 40%;
    left: 36%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 28px !important;
  }
}

/* xl screen */
@media screen and (min-width: 1441px) {
  .id1 {
    width: 14%;
    height: 25%;
    margin: 1%;
    position: absolute;
    top: 67%;
    left: 8.5%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/images.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .id2 {
    width: 14%;
    height: 25%;
    margin: 1%;
    position: absolute;
    top: 67%;
    left: 37.5%;
    transform: translate(100%, -80%);
    background-image: url("@/assets/images.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .license1 {
    width: 30%;
    height: 32%;
    margin: 1%;
    position: absolute;
    top: 30%;
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
    top: 30%;
    left: 10%;
    transform: translate(190%, 44%);
    background-image: url("@/assets/license.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .qr1 {
    width: 9%;
    height: 18%;
    margin: 1%;
    position: absolute;
    top: 91%;
    left: 6.5%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/qr.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .qr2 {
    width: 9%;
    height: 18%;
    margin: 1%;
    position: absolute;
    top: 91%;
    left: 56.5%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/qr.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .control1 {
    position: absolute;
    top: 40%;
    left: 36%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 28px !important;
    font-weight: 1000;
  }
  .control2 {
    position: absolute;
    top: 40%;
    left: 40%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 28px !important;
    font-weight: 1000;
  }
  .name1 {
    position: absolute;
    top: 45%;
    left: 36%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 28px !important;
    font-weight: 1000;
  }
  .name2 {
    position: absolute;
    top: 45%;
    left: 47%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 28px !important;
    font-weight: 1000;
  }
  .contact1 {
  position: absolute;
  top: 57%;
  left: 36%;
  transform: translate(-50%, 1000%);
  color: black !important;
  font-size: 24px !important;
  font-weight: 1000;
}
.contact2 {
  position: absolute;
  top: 57%;
  left: 45%;
  transform: translate(500%, 1000%);
  color: black !important;
  font-size: 24px !important;
  font-weight: 1000;
}
.plate1 {
  position: absolute;
  top: 65%;
  left: 13%;
  transform: translate(-50%, 1000%);
  color: black !important;
  font-size: 24px !important;
  font-weight: 1000;
}
.plate2 {
  position: absolute;
  top: 65%;
  left: 28%;
  transform: translate(500%, 1000%);
  color: black !important;
  font-size: 24px !important;
  font-weight: 1000;
}
.city1 {
  position: absolute;
  top: 65%;
  left: 37%;
  transform: translate(-50%, 1000%);
  color: black !important;
  font-size: 24px !important;
  font-weight: 1000;
}
.city2 {
  position: absolute;
  top: 65%;
  left: 38%;
  transform: translate(500%, 1000%);
  color: black !important;
  font-size: 24px !important;
  font-weight: 1000;
}
.association1 {
  position: absolute;
  top: 29%;
  left: 30%;
  transform: translate(-50%, -80%);
  color: black !important;
  font-size: 28px !important;
  font-weight: 1000;
}
.association2 {
  position: absolute;
  top: 29%;
  left: 80%;
  transform: translate(-50%, -80%);
  color: black !important;
  font-size: 28px !important;
  font-weight: 1000;
}
}
/* Printing */
@media print {
  .qr1 {
    width: 10%;
    height: 13%;
    margin: 1%;
    position: absolute;
    top: 61.5%;
    left: 6.7%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/qr.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .qr2 {
    width: 10%;
    height: 13%;
    margin: 1%;
    position: absolute;
    top: 61.7%;
    left: 56.5%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/qr.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .id2 {
    width: 14%;
    height: 18%;
    margin: 1%;
    position: absolute;
    top: 45.5%;
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
    top: 45.5%;
    left: 8.5%;
    transform: translate(-50%, -80%);
    background-image: url("@/assets/images.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .city1 {
    position: absolute;
    top: 31%;
    left: 37%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 26px !important;
    font-weight: 1000;
  }
  .city2 {
    position: absolute;
    top: 31%;
    left: 15%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 26px !important;
    font-weight: 1000;
  }
  .plate1 {
    position: absolute;
    top: 31%;
    left: 13%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 26px !important;
    font-weight: 1000;
  }
  .plate2 {
    position: absolute;
    top: 31%;
    left: 12%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 26px !important;
    font-weight: 1000;
  }
  .contact1 {
    position: absolute;
    top: 29%;
    left: 36%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 24px !important;
    font-weight: 700;
  }
  .contact2 {
    position: absolute;
    top: 29%;
    left: 31%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 24px !important;
    font-weight: 700;
  }
  .name1 {
    position: absolute;
    top: 25%;
    left: 36%;
    transform: translate(-50%, 1000%);
    color: black !important;
    font-size: 24px !important;
    font-weight: 700;
  }
  .name2 {
    position: absolute;
    top: 25%;
    left: 42%;
    transform: translate(500%, 1000%);
    color: black !important;
    font-size: 24px !important;
    font-weight: 700;
  }
  .control1 {
    position: absolute;
    top: 41%;
    left: 36%;
    transform: translate(-50%, 450%);
    color: black !important;
    font-size: 24px !important;
    font-weight: 700;
  }
  .control2 {
    position: absolute;
    top: 41%;
    left: 33%;
    transform: translate(500%, 450%);
    color: black !important;
    font-size: 24px !important;
    font-weight: 700;
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

  .association1 {
    position: absolute;
    top: 20%;
    left: 30%;
    transform: translate(-50%, -80%);
    color: black !important;
    font-size: 24px !important;
  }
  .association2 {
    position: absolute;
    top: 20%;
    left: 80%;
    transform: translate(-50%, -80%);
    color: black !important;
    font-size: 24px !important;
  }
  .association {
    margin-top: 20%;
    margin-left: 50%;
  }
  .background-container {
    background-image: url("@/assets/bg.jpg");
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
