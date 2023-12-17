<template>
    <UCard class="mt-10">
        <template #header>
          <div class="flex justify-between items-center">
            <h1 class="font-bold">DESKTOP GAMER MAX</h1>
          </div>
        </template>
        <div class="flex justify-evenly items-center">
          <div>
            <img class="w-72 mb-20 " src="@/assets/image/gamer-max.png" alt="">
          </div>
          <div class="w-60 h-48">
            <h1 class="pb-5">
              AMD Ryzen 7 5700X <br>
              Placa Mãe B450 <br>
              RAM DDR4 16GB 3200mhz <br>
              SSD NVMe 1TB <br>
              Nvidia RTX 3060 <br>
            </h1>
            <h1 class="text-red-600 font-bold text-3xl pb-8">R$5.690,00</h1>
            <UButton color="gray" icon="i-heroicons-arrow-right-circle-solid" to="https://ui.nuxt.com" target="_blank">Comprar
            </UButton>
          </div>
        </div>
      </UCard>
</template>