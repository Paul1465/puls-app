<template>
<nav class="bg-gray-800">
  <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
    <div class="relative flex items-center justify-between h-16">
      <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">
        <div class="flex-shrink-0 flex items-center">
          <img class="block lg:hidden h-8 w-auto" src="https://tailwindui.com/img/logos/workflow-mark-indigo-500.svg" alt="Workflow">
          <img class="hidden lg:block h-8 w-auto" src="https://tailwindui.com/img/logos/workflow-logo-indigo-500-mark-white-text.svg" alt="Workflow">
        </div>
      </div>
      <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
        <a href="#" class="text-gray-300 px-3 py-2  text-sm font-medium">Accueil</a>
        <a href="#" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2  text-sm font-medium">Services</a>
        <a href="#" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2  text-sm font-medium" aria-current="page"><span class="active">Véhicules</span></a>
        <a href="#" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2  text-sm font-medium">À propos</a>
        <a href="#" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2  text-sm font-medium">Actualité</a>
        <a href="#" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2  text-sm font-medium">Contact</a>
        <a href="#" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2  text-sm font-medium">Calendar</a>
        <a class="fb-ic ml-4" role="button"><i class="fab fa-md fa-twitter text-white rounded-r-full"></i></a>
        <a class="fb-ic ml-3" role="button"><i class="fab fa-md fa-facebook-square text-white rounded-r-full"></i></a>
        <a class="fb-ic ml-3" role="button"><i class="fab fa-md fa-instagram text-white rounded-r-full"></i></a>
      </div>
    </div>
  </div>
</nav>
</template>
<script>
export default {
  name: "NavBar"
};
</script>
<style>
.active{
  display: inline-block;
  border-bottom: 1px solid #007EDB;
  padding-top: 4px;
  padding-bottom: 2px;
  color: #007EDB;
}
</style>
