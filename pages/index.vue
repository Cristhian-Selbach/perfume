<script></script>
<template>
  <div
    class="bg-[url(~/assets/images/background.jpeg)] w-[100vw] h-[100vh] fixed bg-cover bg-center"
  ></div>
  <Navbar></Navbar>
  <div class="mt-1 z-10 relative w-100 bg-[#4747476a] back backdrop-blur-[3px]">
    <div class="pt-[30vh] flex flex-col items-center">
      <h1 class="font-semibold text-3xl text-white">
        DESCUBRA O AROMA QUE REVELA VOCÊ.
      </h1>
      <a
        href="/produtos"
        class="text-center flex items-center justify-center mt-5 w-[280px] h-[50px] bg-[#FF6F82] border-2 border-[#FF6F82] rounded-xl text-white text-xl hover-effect"
      >
        Explorar a Coleção
      </a>
    </div>
  </div>
</template>
<style>
.back {
  height: calc(100vh - 5.25rem);
}
.hover-effect {
  transition: all 0.15s ease;
}
.hover-effect:hover {
  transform: scale(1.1);
  transition: all 0.3s ease-in-out;
}
</style>
