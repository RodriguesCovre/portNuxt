<template>
  <div class="gallery relative top-80 right-6 ">
    <!-- Left Column -->
    <div class="absolute top-[6em] left-24 flex flex-col space-y-4">
      <div class="card">
        <img class="w-[525px] h-[312px] object-cover" src="../assets/images/poker.png" alt="Poker Image">
      </div>
      <div class="flex space-x-4 ">
        <div class=" relative card ml-28 top-32">
          <img class=" w-[201px] h-[296px] object-cover " src="../assets/images/joaogomes.png" alt="Joao Gomes Image">
        </div>
        <div class="card">
          <img class=" w-[201px] h-[296px] object-cover" src="../assets/images/dashboard.png" alt="Dashboard Image">
        </div>
      </div>
    </div>

    <!-- Center Column -->
    <div class="absolute top-0 left-1/2 transform -translate-x-1/2">
      <div class="card">
        <img class="w-[368px] h-[764px] object-cover" src="../assets/images/carro.png" alt="Car Image">
      </div>
    </div>

    <!-- Right Column -->
    <div class="">
        <img class="w-[201px] h-[296px] object-cover absolute top-[7em] ml-56" src="../assets/images/roleta.png" alt="Roleta Image">
        <img class="w-[482px] h-[296px] object-cover absolute top-[17em] ml-[27.5em]" src="../assets/images/maps.png" alt="Roleta Image">
        <img class="w-[201px] h-[296px] object-cover absolute top-[27em] ml-56" src="../assets/images/wellcome.jpg" alt="Roleta Image">
        <img class="w-[201px] h-[296px] object-cover absolute top-[37em] ml-[29em]" src="../assets/images/nubank.png" alt="Roleta Image">    
    </div>
  </div>
</template>

<style>
.gallery {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
}

.card {
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

img {
  display: block;
  width: 100%;
  height: auto;
}
</style>
