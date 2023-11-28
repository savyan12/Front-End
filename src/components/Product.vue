<template>
  <v-card
    class="mx-auto mt-16 ca"
    max-width="650"
    min-height="10vh"
    rounded="lg"
  >
    <v-row>
      <v-col cols="12" sm="6">
        <img
          id="imge"
          src="../assets/desktop.jpg"
          class="w-100 h-100 h-sm-50 desktop"
          style="object-fit: cover"
        />
        <img
          id="imge"
          src="../assets/mobile.jpg"
          class="w-100 h-100 h-sm-50 d-none mobile"
          style="object-fit: cover"
        />
      </v-col>
      <v-col cols="12" sm="6">
        <div class="nb">
          <h3 class="text-start mt-7 text-blue-grey-lighten-2 Titel r">
            P E R F U M E
          </h3>
          <p class="text-h4 text-start mt-2 w-75 des">
            Gabrielle Essence Eau De Parfum
          </p>
          <p
            style="font-size: 19px"
            class="text-start w-100 text-blue-grey-lighten-2 dd mt-3"
          >
            A florl, aolr and voluptuous interpretation composed by Olivier
            Polge, Perfumer-Creator for the House of CHANEL
            <span id="x" class="d-sm-none">.</span>
          </p>
          <p class="text-start text-h4 mt-5 des" style="color: #3c8168">
            $149.99
            <sup style="font-size: 18px" class="ml-5 Titel text-grey"
              ><del>$169.99</del></sup
            >
          </p>
        </div>

        <v-btn
          color="#3c8168"
          class="mt-8 mb-7 b"
          size="large"
          min-width="80%"
          rounded="small"
          prepend-icon="mdi-cart-outline"
          >Add to cart</v-btn
        >
      </v-col>
    </v-row>
  </v-card>
  <br />
</template>
<script>
export default {
  name: "productApp",
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,400;0,9..144,600;0,9..144,900;1,9..144,800&family=Montserrat:wght@200;300;500&display=swap");
.Titel {
  font-weight: 500;
  font-family: "Montserrat", serif !important;
}
.des {
  font-family: "Fraunces", serif !important;
  font-weight: 700;
}
@media (max-width: 620px) {
  .ca {
    margin: 0 auto !important;
    margin-top: -35px !important;
  }
  #imge {
    max-height: 90%;
  }
  .desktop {
    display: none !important;
  }
  .mobile {
    display: block !important;
  }
  .r {
    margin-top: -25px !important;
  }
  .nb {
    margin-left: 25px;
  }
  .dd {
    width: 75%;
  }
}
</style>
