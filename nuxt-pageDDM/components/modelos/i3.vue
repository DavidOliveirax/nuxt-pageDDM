<template>
    <UCard class="mt-10">
        <template #header>
          <div class="flex justify-between items-center">
            <h1 class="font-bold">DESKTOP HOME</h1>
            <label for="ConfigDesktop" class="block text-sm font-medium text-gray-900"> Headliner </label>
            <select name="ConfigDesktop" id="configDesktop"
              class="mt-1.5 w-30 h-8 rounded-lg border-gray-300 text-white sm:text-sm">
              <option value="">Modelos</option>
              <option value="i3">Home i3</option>
              <option value="i5">Home i5</option>
              <option value="i7">Home i7</option>
            </select>
          </div>
        </template>
        <div class="flex justify-evenly items-center">
          <div>
            <img class="w-72 mb-20 " src="@/assets/image/home-i3.png" alt="">
          </div>
          <div class="w-60 h-48">
            <h1 class="pb-5">
              Intel i3 4160 <br>
              Placa Mãe H81 <br>
              RAM DDR3 8GB 1600mhz <br>
              SSD Sata 256GB <br>
            </h1>
            <h1 class="text-red-600 font-bold text-3xl pb-8">R$1.190,00</h1>
            <UButton color="gray" icon="i-heroicons-arrow-right-circle-solid" to="https://ui.nuxt.com" target="_blank">Comprar
            </UButton>
          </div>
        </div>
      </UCard>
</template>