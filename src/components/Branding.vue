<template>
  <b-container id="products" class="branding" fluid>
    <b-row class="branding__title">
      <h2 class="mt-5">BRANDING</h2>
      <h3 class="mt-3">
        Because every good piece needs to be well accessorized
      </h3>
    </b-row>
    <b-row class="branding__piece mt-4">
      <b-col class="branding__piece__image" md="12" lg="6">
        <img src="../assets/Moonstreet_branding.png" alt="" />
      </b-col>
      <b-col class="branding__piece__description">
        <div>
          <h4>Tajemnice Podwójnego Miasta</h4>
        </div>
        <div class="mt-4">
            Z ekipą z moonstreet znam się od lata 2020 roku, pierwsze co dla nich stworzyłam to dwa plakaty dla ich Warszawskiej gry miejskiej - "Sen" i "Kruk". Kliknęło i od tamtego czasu nieprzerwanie współpracujemy ze sobą tworząc coraz to nowe przygody w różnych miastach w Polsce. Ja oczywiście odpowiedzialna jestem za całą część kreatywną tego projektu, w tym przypadku byłam odpowiedzialna za wszystkie rekwizyty i motywy Sekretów Podwójnego Miasta we Wrocławiu, gdzie gracz wciela się w rolę wybrańca, który ma zostać nowym królem Wrocławia, wszystkim steruje tajne Stowarzyszenie 3 Mojry - stąd motyw trzech kobiet oraz królewskiej korony, rekwizyty dodatkowo wyposażone są w wiele zagadek, które uczestnik odkrywa kawałek po kawałku..
        </div>
      </b-col>
    </b-row>
    <b-row class="branding__piece__reversed mt-4">
      <b-col class="branding__piece__image" md="12" lg="6">
        <img src="../assets/Dart-branding.png" alt="" />
      </b-col>
      <b-col class="branding__piece__description">
        <div style="text-align:end;">
          <h4>Drones And Robots Tournament</h4>
        </div>
        <div class="mt-4" style="text-align:end;">
          Tutaj będzie ładny opis produktu :) Póki co proszę podziwiać grafiki. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse lacinia lorem nec nibh venenatis pharetra. Phasellus eleifend, massa viverra vehicula aliquet, ipsum lectus dignissim tortor, mollis semper nibh justo eget elit. Donec vehicula pretium accumsan. In purus massa, ultrices nec orci eget, fringilla fermentum metus. Integer cursus turpis vel libero convallis, in vestibulum felis venenatis. Phasellus tristique erat eu felis laoreet, nec semper massa fermentum. 
        </div>
      </b-col>
    </b-row>
    <b-row class="branding__piece mt-4">
      <b-col class="branding__piece__image" md="12" lg="6">
        <img src="../assets/Cirque_branding.png" alt="" />
      </b-col>
      <b-col class="branding__piece__description">
        <div>
          <h4>Cirque Du So-Lou</h4>
        </div>
        <div class="mt-4">
          Tutaj również w przyszłości pojawi się opis. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse lacinia lorem nec nibh venenatis pharetra. Phasellus eleifend, massa viverra vehicula aliquet, ipsum lectus dignissim tortor, mollis semper nibh justo eget elit. Donec vehicula pretium accumsan. In purus massa, ultrices nec orci eget, fringilla fermentum metus. Integer cursus turpis vel libero convallis, in vestibulum felis venenatis. Phasellus tristique erat eu felis laoreet, nec semper massa fermentum. 
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.branding {
  background-color: white;
  @include media-breakpoint-up(md) {
    padding: 0 10%;
  }
  &__title {
    display: flex;
    flex-direction: column;
    align-content: center;
    text-align: center;
    padding: 0 15px;
    h2 {
      text-align: center;
      letter-spacing: 6px;
      font-size: 2.8rem;
      font-weight: 600;
    }
    h3 {
      font-size: 1.2rem;
      font-weight: normal;
    }
  }
  &__piece {
    img {
      width: 100%;
    }
    &__description {
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    &__reversed {
      flex-direction: row-reverse;
      @include media-breakpoint-down(md) {
        flex-direction: row;
      }
      img {
        width: 100%;
      }
    }
  }
}
</style>
