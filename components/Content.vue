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
              style="height: 575px; background-image: url(https://mdbootstrap.com/img/new/slides/052.jpg)"
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
          <div class="col-end-6 col-span-2 text-gray-400 font-semibold text-base ml-6">
            <p>à partir de</p>
            <span class="font-bold text-lg">218 €</span> /mois
            <i class="fa fa-xs fa-info-circle" aria-hidden="true"></i>
          </div>
        </div>
        <hr class="text-gray-300 w-5/6 content-center mb-7 -mt-2" />
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

    <div class="grid grid-cols-3 gap-4 mt-10">
      <div class="col-span-2 border-right-grey ml-10">
        <h3 class="font-semibold text-2xl mb-3">Fiche technique</h3>
        <h4 class="font-semibold text-1x1 mb-3">Général</h4>
        <div class="grid grid-cols-4 gap-5 row-color-grey mr-10 mb-2">
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
        <div class="grid grid-cols-4 gap-5 row-color-grey mr-10 mb-10">
          <div class="text-gray-500">Carrosserie</div>
          <div>5 portes</div>
          <div class="text-gray-500">Couleur</div>
          <div>Noir</div>
        </div>
        <div class="grid grid-cols-2 gap-5 mr-10 mb-4">
          <h4 class="font-semibold text-1x1 mb-3">Consommation</h4>
          <h4 class="font-semibold text-1x1 mb-3">Informations énergétiques</h4>
        </div>
        <div class="grid grid-cols-4 gap-5 row-color-grey mr-10 mb-2">
          <div class="text-gray-500">Mixte</div>
          <div>4.7 1/ 100 Km</div>
          <div class="text-gray-500">Emissions de CO2</div>
          <div class="flex flex-row">  108g / Km 
          <svg class="mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
            width="18" height="18"
            viewBox="0 0 172 172"
            style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#1bd261"><path d="M87.47672,14.29834c-39.5815,0 -71.66667,32.08517 -71.66667,71.66667c0,39.5815 32.08517,71.66667 71.66667,71.66667c39.5815,0 71.66667,-32.08517 71.66667,-71.66667c0,-39.5815 -32.08517,-71.66667 -71.66667,-71.66667zM69.868,50.18766h24.13151c11.35558,0 20.59717,9.238 20.59717,20.59717c0,5.21017 -1.94054,9.97197 -5.14404,13.60547c0.96392,0.68083 1.87324,1.45315 2.72249,2.30957c3.8915,3.90583 6.02297,9.09153 5.99788,14.60628c-0.05375,11.27317 -9.2716,20.46027 -20.54118,20.47819l-27.75684,0.04899h-0.007c-1.42258,0 -2.78979,-0.56079 -3.80029,-1.56771c-1.0105,-1.00692 -1.57471,-2.37754 -1.57471,-3.80729v-60.89567c0,-2.967 2.40442,-5.375 5.375,-5.375zM75.243,60.93766v19.70134l18.76351,-0.007c5.43233,0 9.84017,-4.41842 9.84017,-9.84717c0,-5.43233 -4.41842,-9.84717 -9.84717,-9.84717zM75.243,91.389v19.68034l22.37484,-0.03499c5.38216,-0.01075 9.78351,-4.39502 9.81217,-9.77718c0.01075,-2.63375 -1.00272,-5.11437 -2.86247,-6.9777c-1.85975,-1.86333 -4.34054,-2.89046 -6.9707,-2.89046z"></path></g></g></svg>
          </div>
        </div>
        <div class="grid grid-cols-4 gap-5 mr-10 mb-10">
          <div class="text-gray-500">Extra-urbaine</div>
          <div>3.8 1 / 100 Km</div>
          <div class="text-gray-500">Qualité de l'air</div>
          <div class="flex flex-row">Crit'Air Niveau 1
          <svg class="mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
            width="18" height="18"
            viewBox="0 0 172 172"
            style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#8f40ff"><path d="M86,14.33333c-39.41667,0 -71.66667,32.25 -71.66667,71.66667c0,39.41667 32.25,71.66667 71.66667,71.66667c39.41667,0 71.66667,-32.25 71.66667,-71.66667c0,-39.41667 -32.25,-71.66667 -71.66667,-71.66667zM88.86667,118.96667v0c-3.56183,0 -6.45,-2.88817 -6.45,-6.45v-44.43333l-8.97983,2.8595c-3.36117,1.06783 -6.78683,-1.4405 -6.78683,-4.95933v0c0,-2.17867 1.36167,-4.128 3.40417,-4.88767l23.82917,-8.77917h1.43333v60.2c0,3.56183 -2.88817,6.45 -6.45,6.45z"></path></g></g></svg>
          </div>
        </div>

        <h3 class="font-semibold text-2xl mb-6">Equipements</h3>
        <div class="grid grid-cols-2 gap-5 row-color-grey mr-10 mb-2">
          <div>Climatisation</div>
          <div>GPS</div>
        </div>
        <div class="grid grid-cols-2 gap-5 mr-10 mb-2">
          <div>Jantes Alus</div>
          <div>Phares xénon</div>
        </div>
        <div class="grid grid-cols-2 gap-5 row-color-grey mr-10 mb-2">
          <div>Régulateur de vitesse</div>
          <div>Prises USB</div>
        </div>
        <div class="grid grid-cols-2 gap-5 mr-10 mb-2">
          <div>Bluetooth</div>
          <div>Feux automatiques</div>
        </div>
        <div class="grid grid-cols-2 gap-5 row-color-grey mr-10 mb-2">
          <div>Capteur de pluie</div>
          <div>Radar de recul arrière</div>
        </div>
        <div class="grid grid-cols-2 gap-5 mr-10 mb-2">
          <div>Radar de recul avant/arrière</div>
          <div>Courroie de Distribution</div>
        </div>
        <div class="grid grid-cols-1 gap-5 row-color-grey mr-10 mb-14">
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
        <div class="grid grid-cols-2 gap-5 mr-6 mb-1 mt-4 ml-6">
          <div class="primary-font text-1xl font-semibold mt-1">Peugeot</div>
          <div class="text-2xl font-bold text-right">28 270 €</div>
        </div>
        <div class="grid grid-cols-4 gap-2 mr-6 mb-2 mt-1 ml-6">
          <div class="col-span-3">
            <p class="font-bold text-lg">208 5 places</p>
            <p class="text-sm mt-1">1.2 PureTech 82 BVM5</p>
            <p class="text-sm font-normal mt-3">
              <span class="mr-2">2019</span>|
              <span class="mr-2 ml-2">Essence</span>|
              <span class="mr-2 ml-2">10km</span>
            </p>
          </div>
          <div class="text-gray-400 text-xs font-semibold text-right mt-1">
            <p>à partir</p>
            <span class="font-bold text-base-without-line-height -my-1">240 €</span>
            <p class="-mt-1">/mois</p>
          </div>
        </div>

        <div class="grid grid-cols-2 bg-blue-200 mt-7 mb-8">
          <button
            class="btn color-link hover:bg-blue-400 text-white w-100 text-sm py-2 px-1"
          >
            <i class="fa fa-car mr-1" aria-hidden="true"></i>
            Voir le détail
          </button>
          <button
            class="btn color-link hover:bg-blue-400 text-white w-100 text-sm py-2 px-1"
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
.row-color-grey{
  background-color: #F6F6F6;
}
.color-link {
  color: #1371c3;
}
.text-base-without-line-height{
font-size: 1rem;
}
</style>
