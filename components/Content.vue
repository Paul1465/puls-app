<template>
  <div>
    <NavBar />
    <div class="grid grid-cols-3 gap-4">
      <div class="col-span-2 border-right-grey">
        <div
          class="carousel relative rounded relative overflow-hidden shadow-xl"
        >
          <div class="carousel-inner relative overflow-hidden w-full">
            <!--Slide 1-->
            <input
              class="carousel-open"
              type="radio"
              id="carousel-1"
              name="carousel"
              aria-hidden="true"
              hidden=""
              checked="checked"
            />
            <div
              class="carousel-item absolute opacity-0 bg-center"
              style="height:500px; background-image: url(https://mdbootstrap.com/img/new/slides/052.jpg)"
            ></div>
            <label
              for="carousel-3"
              class="control-1 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 left-0 my-auto flex justify-center content-center"
              ><i class="fas fa-angle-left mt-3"></i
            ></label>
            <label
              for="carousel-2"
              class="next control-1 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
              ><i class="fas fa-angle-right mt-3"></i
            ></label>

            <!--Slide 2-->
            <input
              class="carousel-open"
              type="radio"
              id="carousel-2"
              name="carousel"
              aria-hidden="true"
              hidden=""
            />
            <div
              class="carousel-item absolute opacity-0 bg-center"
              style="height:500px; background-image: url(https://mdbootstrap.com/img/new/slides/043.jpg)"
            ></div>
            <label
              for="carousel-1"
              class=" control-2 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
              ><i class="fas fa-angle-left mt-3"></i
            ></label>
            <label
              for="carousel-3"
              class="next control-2 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
              ><i class="fas fa-angle-right mt-3"></i
            ></label>

            <!--Slide 3-->
            <input
              class="carousel-open"
              type="radio"
              id="carousel-3"
              name="carousel"
              aria-hidden="true"
              hidden=""
            />
            <div
              class="carousel-item absolute opacity-0"
              style="height:500px; background-image: url(https://mdbootstrap.com/img/new/slides/054.jpg)"
            ></div>
            <label
              for="carousel-2"
              class="control-3 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
              ><i class="fas fa-angle-left mt-3 fa-5"></i
            ></label>
            <label
              for="carousel-1"
              class="next control-3 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
              ><i class="fas fa-angle-right mt-3"></i
            ></label>
          </div>
        </div>
      </div>
      <div class="container mt-5 ml-5">
        <p class="font-semibold">
          <i class="fa fa-chevron-left mr-2" aria-hidden="true"></i>
          Retourner aux véhicules
        </p>
        <br class="mt-5" />
        <h3 class="primary-font text-3xl mt-5">PEUGEOT</h3>
        <p class="text-5xl font-bold mt-1">208</p>
        <p class="text-3xl font-medium mt-1">1.2 PureTech 82 BVM5</p>
        <p class="text-2x1 font-normal mt-3">
          <span class="ml-1 mr-3 mt-3 mb-3">2019</span>|
          <span class="m-3">Essence</span>| <span class="m-3">10km</span>|
          <span class="m-3">Automatique</span>
        </p>
        <hr class="text-gray-300 w-5/6 content-center mt-10 mb-5" />
        <div class="grid grid-cols-6 gap-4 mb-10">
          <div class="col-start-1 col-end-4 text-5xl font-bold mt-1">
            11 600 €
          </div>
          <div class="col-end-6 col-span-2 text-gray-400 text-lg ml-9">
            <p>à partir de</p>
            <span class="font-bold">218 €</span> /mois
            <i class="fa fa-xs fa-info-circle" aria-hidden="true"></i>
          </div>
        </div>
        <hr class="text-gray-300 w-5/6 content-center mt-5 mb-7" />
        <div class="mr-14">
          <button
            class="btn btn-primary bg-blue-500 hover:bg-blue-700 text-white font-bold border btn-block w-100 py-4 px-12 mb-3 mr-5"
          >
            Acheter ce véhicule
          </button>
          <button
            class="btn btn-primary bg-blue-500 hover:bg-blue-700 text-white font-bold border btn-block py-4 px-12"
          >
            <i class="fa fa-heart mr-3" aria-hidden="true"></i>
            Mettre en favori
          </button>
        </div>
      </div>
    </div>

    <div class="grid grid-cols-3 gap-4">
      <div class="col-span-2 border-right-grey ml-10">
        <h3 class="font-semibold text-2xl mb-3">Fiche technique</h3>
        <h4 class="font-semibold text-1x1 mb-3">Général</h4>
        <div class="grid grid-cols-4 gap-5 row-color-beige mr-10 mb-2">
          <div class="text-gray-500">Type</div>
          <div>Citadine</div>
          <div class="text-gray-500">Puissance</div>
          <div>6 CV / 112 ch</div>
        </div>
        <div class="grid grid-cols-4 gap-5 mr-10 mb-2">
          <div class="text-gray-500">Garantie</div>
          <div>6 mois</div>
          <div class="text-gray-500">Première main</div>
          <div>Oui</div>
        </div>
        <div class="grid grid-cols-4 gap-5 row-color-beige mr-10 mb-10">
          <div class="text-gray-500">Carrosserie</div>
          <div>5 portes</div>
          <div class="text-gray-500">Couleur</div>
          <div>Noir</div>
        </div>
        <div class="grid grid-cols-2 gap-5 mr-10 mb-4">
          <h4 class="font-semibold text-1x1 mb-3">Consommation</h4>
          <h4 class="font-semibold text-1x1 mb-3">Informations énergétiques</h4>
        </div>
        <div class="grid grid-cols-4 gap-5 row-color-beige mr-10 mb-2">
          <div class="text-gray-500">Mixte</div>
          <div>4.7 1/ 100 Km</div>
          <div class="text-gray-500">Emissions de CO2</div>
          <div>108g / Km</div>
        </div>
        <div class="grid grid-cols-4 gap-5 mr-10 mb-10">
          <div class="text-gray-500">Extra-urbaine</div>
          <div>3.8 1 / 100 Km</div>
          <div class="text-gray-500">Qualité de l'air</div>
          <div>Crit'Air Niveau 1</div>
        </div>

        <h3 class="font-semibold text-2xl mb-5">Equipements</h3>
        <div class="grid grid-cols-2 gap-5 row-color-beige mr-10 mb-2">
          <div>Climatisation</div>
          <div>GPS</div>
        </div>
        <div class="grid grid-cols-2 gap-5 mr-10 mb-2">
          <div>Jantes Alus</div>
          <div>Phares xénon</div>
        </div>
        <div class="grid grid-cols-2 gap-5 row-color-beige mr-10 mb-2">
          <div>Régulateur de vitesse</div>
          <div>Prises USB</div>
        </div>
        <div class="grid grid-cols-2 gap-5 mr-10 mb-2">
          <div>Bluetooth</div>
          <div>Feux automatiques</div>
        </div>
        <div class="grid grid-cols-2 gap-5 row-color-beige mr-10 mb-2">
          <div>Capteur de pluie</div>
          <div>Radar de recul arrière</div>
        </div>
        <div class="grid grid-cols-2 gap-5 mr-10 mb-2">
          <div>Radar de recul avant/arrière</div>
          <div>Courroie de Distribution</div>
        </div>
        <div class="grid grid-cols-1 gap-5 row-color-beige mr-10 mb-14">
          <div>Caméra de recul</div>
        </div>
      </div>
      <div class="col-span-2 ml-10">
        <h3 class="font-semibold text-2xl mb-10">Véhicules similaires</h3>
      </div>
    </div>

    <div class="grid grid-cols-4 gap-5 ml-10">
      <div
        v-for="cards in 4"
        :key="cards"
        class="max-w-sm rounded overflow-hidden bg-gray-100"
      >
        <img
          class="w-full"
          src="https://mdbootstrap.com/img/new/slides/043.jpg"
          alt="Sunset in the mountains"
        />
        <div class="grid grid-cols-2 gap-5 mr-10 mb-1 mt-5 ml-10">
          <div class="primary-font text-1xl font-semibold mt-1">Peugeot</div>
          <div class="text-2xl font-bold text-right">28 270 €</div>
        </div>
        <div class="grid grid-cols-2 mr-10 mb-2 mt-5 ml-10">
          <div class="text-2xl font-bold width-block">
            <p>208 5 places</p>
            <p class="text-base font-medium mt-1">1.2 PureTech 82 BVM5</p>
            <p class="text-base texy-base font-normal mt-3">
              <span class="mr-2">2019</span>|
              <span class="mr-2 ml-2">Essence</span>|
              <span class="mr-2 ml-2">10km</span>
            </p>
          </div>
          <div class="text-gray-400 text-sm text-right mt-1">
            <p>à partir</p>
            <span class="font-bold text-xl">218 €</span>
            <p>/mois</p>
          </div>
        </div>

        <div class="grid grid-cols-2 mt-8">
          <button
            class="btn bg-blue-200 color-link hover:bg-blue-400 text-white border w-100 text-1xl"
          >
            <i class="fa fa-car mr-1" aria-hidden="true"></i>
            Voir le détail
          </button>
          <button
            class="btn bg-blue-200 color-link hover:bg-blue-400 text-white border w-100 py-2"
          >
            <i class="fa fa-heart mr-1" aria-hidden="true"></i>
            Mettre en favori
          </button>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import NavBar from "~/components/NavBar";
import Footer from "~/components/Footer";
export default {
  components: {
    NavBar,
    Footer
  }
};
</script>

<style>
.primary-font {
  color: #007edb;
}
.btn-block {
  display: block;
  text-align: center;
  width: 100%;
  background-color: #007edb;
}
.border-right-grey {
  border-right: 1px solid #d3d3d3;
}
.row-color-beige {
  background-color: #f5dcf5;
}
.width-block {
  width: 130%;
}
.color-link {
  color: #1371c3;
}
</style>
