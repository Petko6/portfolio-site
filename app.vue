<template>
  <div class="snap-y snap-mandatory h-screen overflow-y-scroll scroll-smooth">
    <div id="domov"
      class="snap-start hero h-screen bg-center sm:bg-center xl:bg-[center_top_-14rem] bg-no-repeat sm:bg-[url('~/assets/css/main.png')] bg-[url('~/assets/css/main-sm.png')] z-[1]">
      <div
        class="w-full row-start-1 col-start-1 bg-opacity-100 bg-gradient-to-t from-base-100 to-transparent place-self-end h-56 bottom-0 z-[2]">
      </div>
      <div class="hero-overlay bg-black bg-opacity-40"></div>
      <header
        class="place-self-start justify-self-end mx-6 sm:mx-8 my-4 grid gap-3 grid-flow-col fixed z-50 border-b-2 drop-shadow shadow-xl text-xl sm:text-2xl">
        <a class="hover:text-white drop-shadow-xl" href="#domov">Domů</a>
        <a class="hover:text-white drop-shadow-xl" href="#projekty">Projekty</a>
        <a class="hover:text-white drop-shadow-xl" href="#kontakt">Kontakt</a>
      </header>

      <div class="max-w-md text-center text-white z-10 place-self-start justify-self-center mt-24">
        <h1 class="text-5xl font-bold">Petr Procházka</h1>
        <p class="py-6 text-xl">Web_development&nbsp;&nbsp;&nbsp;Programování</p>
      </div>
      <div class="hidden place-self-end justify-self-center mb-60 lg:mb-56"><a href="#projekty"> <button
            class="end btn btn-accent btn-outline rounded-none text-2xl font-normal border-[3px] border-white bg-black/40">Zobrazit
            Projekty</button></a></div>
    </div>
    <div id="projekty" class="snap-start h-screen z-0 hero">
      <div class="max-w-md text-center mb-0">
        <h1 class="text-5xl font-bold mb-8 text-white">Projekty</h1>
        <div class="grid grid-flow-row grid-cols-2 sm:grid-cols-3 gap-20 text-xl">
          <a class="hover:text-white" href="/projekty/krkonose/index.html">Krkonoše</a>
          <a class="hover:text-white" href="/projekty/sachovnice/index.html">Šachovnice</a>
          <a class="hover:text-white" href="/projekty/kalendar/index.html">Kalendář</a>
          <a class="hover:text-white" href="/projekty/form/index.html">Formulář</a>
        </div>
      </div>
    </div>
    <div id="kontakt" class="snap-start h-screen z-0 hero">
      <div class="max-w-lg text-center z-10 mb-0">
        <h1 class="text-5xl font-bold mb-8 text-white">Kontakt</h1>
        <div class="text-xl hover:text-white">
          <a href="mailto:p.prochazka.06@gmail.com">p.prochazka.06@gmail.com</a>
        </div>
      </div>
    </div>
  </div>
</template>
