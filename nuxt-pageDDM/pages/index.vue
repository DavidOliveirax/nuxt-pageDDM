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
          <div class="flex justify-between">
            <h1>Desktop Home</h1>
            <ColorScheme>
              <USelect v-model="$colorMode.preference" :options="['system', 'light', 'dark']" />
            </ColorScheme>
          </div>
        </template>
        <div class="flex justify-evenly items-center">
          <div>
            <img class="w-72 mb-20 " src="@/assets/image/home-i3.png" alt="">
          </div>
          <div>
            <h1 class="pb-5">
              Desktop HOME i3 <br>
              Intel i3 4160 / RAM DDR3 8GB <br>
              SSD 256GB / Placa Mãe H61 <br>
            </h1>
            <UButton icon="i-heroicons-arrow-right-circle-solid" to="https://ui.nuxt.com" target="_blank">Comprar
            </UButton>
          </div>
        </div>
      </UCard>
    </UContainer>
  </div>
</template>

<script></script>

<style></style>