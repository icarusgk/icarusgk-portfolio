<script lang="ts" setup></script>

<template>
  <div class="flex <xl:justify-center justify-between w-screen pl-20 py-12 <xl:pl-0">
    <!-- <div class=""> -->
      <ul class="flex items-center gap-20 <xl:hidden">
        <li class="font-medium text-xl">About me</li>
        <li class="font-medium text-xl">Projects</li>
      </ul>
      <!-- Toggle Dark/Light mode -->
      <div class="flex items-center pr-10 <md:pr-0 justify-center">
        <div class="mr-10 h-3 w-96 <md:w-28 bg-black rounded"></div>
        <img class="w-80 <md:w-50" src="/icarus-logo.svg" alt="icarus.gk logo" />
        <div class="h-3 w-28 <md:ml-10 bg-black rounded"></div>
      </div>
    <!-- </div> -->
  </div>
</template>
