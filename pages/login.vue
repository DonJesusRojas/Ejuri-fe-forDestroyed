<script lang="ts" setup></script>

<template>
  <div class="h-screen h-screen flex items-center justify-center  ">
    <div
    class="flex flex-col mx-auto items-center justify-center space-y-4 shadow-2xl w-80  h-[450px] rounded-[30px]"
  >
    <div class="flex flex-col items-center justify-center">
      <nuxt-img src="logo.png" width="100px" class="mx-auto" />
      <span class="text-xl font-bold">Ejuri</span>
    </div>
    <div class="flex flex-col items-center justify-center space-y-4">
      <div class="flex flex-col items-center justify-center">
        <span class="text-xl font-semibold">Iniciar sesión</span>
      </div>
      <div class="flex flex-col items-center justify-center">
        <input
          type="text"
          placeholder="Usuario"
          class="border border-gray-300 text-center rounded-full focus:outline-none focus:border-[#A3DEE0] p-2 m-2"
        />
        <input
          type="password"
          placeholder="Contraseña"
          class="border border-gray-300 text-center rounded-full focus:outline-none focus:border-[#A3DEE0] p-2 m-2"
        />
      </div>
      <div class="flex flex-col items-center justify-center">
        <button
          class="bg-teal-500 text-gray-700 text-sm font-bold py-2 px-4 rounded-full hover:bg-[#3f51b5] hover:text-white transition duration-300"
        >
          Iniciar sesión
        </button>
      </div>
    </div>
  </div>
  </div>
</template>
