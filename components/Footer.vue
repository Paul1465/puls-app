<template>
    <footer class="bg-gray-800 text-white body-font mt-14">
        <div
        class="container px-5 py-14 mx-auto flex md:items-center lg:items-start md:flex-row md:flex-nowrap flex-wrap flex-col">
            <div class="w-64 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left">
                <a href="" class="flex title-font font-medium items-center md:justify-start justify-center">
                    <span class="ml-10 text-xl">GARAGE RENAULT</span>
                </a>
            </div>
            <div class="flex-grow flex flex-wrap md:pl-20 -mb-10 md:mt-0 mt-10 md:text-left text-center">
                <div class="lg:w-1/4 md:w-1/2 w-full px-4">
                <h2 class="title-font font-semibold tracking-widest text-xl mb-3">Navigation</h2>
                    <nav class="list-none mb-10">
                        <li>
                            <a href="#" class="font-medium">Accueil</a>
                        </li>
                        <li>
                            <a href="#" class="font-medium">Services</a>
                        </li>
                        <li>
                            <a href="#" class="font-medium">Véhicules</a>
                        </li>
                        <li>
                            <a href="#" class="font-medium">À propos</a>
                        </li>
                    </nav>
                </div>
                <div class="lg:w-1/4 md:w-1/2 w-full px-4">
                    <nav class="list-none mb-10 mt-10">
                        <li>
                            <a href="#" class="font-medium">Actualité</a>
                        </li>
                        <li>
                            <a href="#" class="font-medium">Contact</a>
                        </li>
                        <li>
                            <a href="#" class="font-medium">Politique de confidentialité</a>
                        </li>
                        <li>
                            <a href="#" class="font-medium">Mention légales</a>
                        </li>
                    </nav>
                </div>
                <div class="lg:w-2/4 md:w-1/2 w-full px-4 text-right content-end right-0 items-end  text-xl font-semibold">
                    <h1>Suivez-nous</h1>
                        <div class="grid grid-cols-3 mr-2">
                        <div class="flex flex-row mt-5 col-start-3 col-end-5">
                            <a class="rounded-full bg-blue-circle h-11 w-11 flex items-center justify-center fb-ic ml-3" role="button"><i class="fab fa-md fa-facebook-square text-white rounded-r-full"></i></a>
                            <a class="rounded-full bg-blue-circle h-11 w-11 flex items-center justify-center fb-ic ml-4" role="button"><i class="fab fa-md fa-twitter text-white rounded-r-full"></i></a>
                            <a class="rounded-full bg-blue-circle h-11 w-11 flex items-center justify-center fb-ic ml-3" role="button"><i class="fab fa-md fa-instagram text-white rounded-r-full"></i></a>
                        </div>
                        </div>
                </div>
                <div class="container mx-auto flex flex-wrap flex-col sm:flex-row ml-4 mb-10">
                    <p class="text-gray-500 text-xs text-center sm:text-left">
                    © Marketing automobile by Le Garage Digital, powered by Eveho
                    </p>
                </div>  
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer"
};
</script>

<style>
.bg-blue-circle{
    background-color: #007EDB;
}
</style>