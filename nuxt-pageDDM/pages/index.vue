<template>
  <div>
    <Header />
  </div>
  <div class="h-96 flex justify-center items-center">
    <section>
      <h1
        class="bg-gradient-to-r from-gray-400 via-red-400 to-red-600 bg-clip-text text-3xl font-extrabold text-transparent sm:text-5xl">
        O SEU DESKTOP ESTÁ AQUI!
      </h1>
    </section>
  </div>
  <div>
    <UContainer>
      <UCard class="mt-10">
        <template #header>
          <div class="flex justify-between items-center">
            <h1 class="font-bold">DESKTOP HOME</h1>
            <label for="ConfigDesktop" class="block text-sm font-medium text-gray-900"> Headliner </label>
            <select name="ConfigDesktop" id="configDesktop"
              class="mt-1.5 w-30 h-8 rounded-lg border-gray-300 text-white sm:text-sm">
              <option value="i3">Configurações</option>
              <option value="i3">Desktop i3</option>
              <option value="i5">Desktop i5</option>
              <option value="i7">Desktop i7</option>
            </select>
          </div>
        </template>
        <div id="configD" class="flex justify-evenly items-center">
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
      <UCard class="mt-10">
        <template #header>
          <div class="flex justify-between items-center">
            <h1 class="font-bold">DESKTOP GAMER MID</h1>
          </div>
        </template>
        <div class="flex justify-evenly items-center">
          <div>
            <img class="w-72 mb-20" src="@/assets/image/gamer-mid.png" alt="">
          </div>
          <div class="w-60 h-48">
            <h1 class="pb-5">
              AMD Ryzen 5 5600G <br>
              Placa Mãe B450 <br>
              RAM DDR4 16GB 3200mhz <br>
              SSD NVMe 500GB <br>
            </h1>
            <h1 class="text-red-600 font-bold text-3xl pb-8">R$3.190,00</h1>
            <UButton color="gray" icon="i-heroicons-arrow-right-circle-solid" to="https://ui.nuxt.com" target="_blank">Comprar
            </UButton>
          </div>
        </div>
      </UCard>
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
    </UContainer>
  </div>
  <div>
    <Footer />
  </div>
</template>

<script>
</script>

<style></style>