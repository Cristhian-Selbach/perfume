<template>
  <div>
    <Navbar></Navbar>
    <div class="mx-32 mt-16">
      <div class="flex">
        <div
          class="flex items-center justify-center w-[420px] h-[460px] bg-[#d4d4d4] rounded-xl card"
        >
          <img class="w-[80%]" src="~/assets/images/eudora.png" alt="" />
        </div>
        <div class="ml-8 mt-8 texts max-w-[50%]">
          <h1 class="text-3xl font-bold">Eudora Rosé Eau de Parfum 75ml</h1>
          <p class="my-5 text-lg font-semibold">
            Eudora Rosé Eau de Parfum traz o impacto borbulhante do espumante
            para criar um Chypre Frutal sofisticado e intenso, com boa fixação.
          </p>
          <h1 class="text-3xl font-bold">R$ 254,90</h1>
          <div class="flex">
            <div
              class="p-3 text-center flex items-center justify-between mt-5 w-[100px] border-black border-2 h-[40px] rounded-xl text-xl"
            >
              <p class="text-3xl cursor-pointer">-</p>
              <p>1</p>
              <p class="text-2xl cursor-pointer">+</p>
            </div>
            <a
              href="#"
              class="ml-5 text-center flex items-center justify-center mt-5 w-[230px] h-[40px] bg-[#FF6F82] rounded-xl text-white text-xl hover-effect"
            >
              COMPRAR
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
