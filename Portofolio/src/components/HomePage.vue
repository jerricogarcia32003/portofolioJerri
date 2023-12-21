<template>
  <div class="main-container flex overflow-x-hidden">
    <div class="container-1 bg-green-500 w-1/2 h-full p-4 box-border">
      <h1>Hi</h1>
      <div class="profile">
        Dit is een faketekst. Alles wat hier staat is slechts om een indruk te geven van het grafische effect van tekst op deze plek. Wat u hier leest is een voorbeeldtekst. Deze wordt later vervangen door de uiteindelijke tekst, die nu nog niet bekend is. De faketekst is dus een tekst die eigenlijk nergens over gaat. Het grappige is, dat mensen deze toch vaak lezen. Zelfs als men weet dat het om een faketekst gaat, lezen ze toch door.
      </div>
    </div>
    <div class="container-2 bg-red-500 w-1/2 h-full p-4 box-border">
      <div class="photos">
        Dit is een faketekst. Alles wat hier staat is slechts om een indruk te geven van het grafische effect van tekst op deze plek. Wat u hier leest is een voorbeeldtekst. Deze wordt later vervangen door de uiteindelijke tekst, die nu nog niet bekend is. De faketekst is dus een tekst die eigenlijk nergens over gaat. Het grappige is, dat mensen deze toch vaak lezen. Zelfs als men weet dat het om een faketekst gaat, lezen ze toch door.
      </div>
    </div>
  </div>
</template>
<script>

</script>

<style scoped>

body,
html {
  margin: 0;
  padding: 0;
  overflow-x: hidden; 
}


.main-container {
  display: flex;
  width: 100vw; 
  height: 100vh;
  overflow-x: hidden; 
}


.container-1 {
  background-color: Green;
  width: 50%;
  height: 100%;
  
  box-sizing: border-box;
}

.container-2 {
  background-color: Red;
  width: 50%;
  height: 100%;

  box-sizing: border-box;
}

</style>
