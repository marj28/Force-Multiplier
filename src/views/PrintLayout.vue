<template>
  <div>
    <div class="ma-4 row" >
      <v-row no-gutters >
        <v-col>
          <v-container class="background-container" >
            <!-- <v-layout fill-height justify-center align-center>
              <v-flex text-xs-center>
                <h1 class="text-overlay">Your Text Here</h1>
              </v-flex>
            </v-layout> -->
            <h5 class="association">Dria ang Association</h5>
            <!-- <h4 class="association">Dria ang Association</h4>
            <h4 class="controlNo ">123456</h4>
            <h4 class="fullName ">Honey Marjey Curay</h4>
            <h4 class="contactNo ">0912345678</h4> -->
          </v-container>
        </v-col>
        <v-col>
          <v-container class="background-container ml-1" >
            <!-- <v-layout fill-height justify-center align-center>
              <v-flex text-xs-center>
                <h1 class="text-overlay">Your Text Here</h1>
              </v-flex>
            </v-layout> -->
            <v-flex>
              <h5 class="association">Dria ang Association</h5>
            </v-flex>

            <!-- <h4 class="association">Dria ang Association</h4>
            <h4 class="controlNo ">123456</h4>
            <h4 class="fullName ">Honey Marjey Curay</h4>
            <h4 class="contactNo ">0912345678</h4> -->
          </v-container>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script setup></script>
<style>
.association {
  margin-top: 24%;
  margin-left: 50%;
}
.controlNo {
  margin-top: 59%;
  margin-left: 40%;
}
.contactNo {
  margin-top: 2%;
  margin-left: 40%;
}
.fullName {
  margin-top: 1%;
  margin-left: 40%;
}
.background-container {
  background-image: url("@/assets/image.png");
  background-size: cover;
  background-repeat: no-repeat;
  height: 500%;
}

.text-overlay {
  color: white;
  font-size: 36px;
}

@page {
  size: landscape;
}

@media print {
  .association {
  margin-top: 20%;
  margin-left: 50%;
}
  @page {

    size: 8.5in 11in landscape;
  }

  #print-area {
    size: 100%;
    margin: 0.22 0.31 0.96 0.31 !important;
  }

  /* #image {
    height: 100% !important;
    width: 100% !important;
  } */
}
</style>
