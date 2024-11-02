<section class="relative h-screen flex items-center justify-center text-center text-white">
  <!-- Background Image with Overlay -->
  <div 
    class="absolute inset-0 bg-cover bg-center opacity-90" 
    style="background-image: url('/assets/building.jpg');"
  ></div>
  
  <!-- Centered Text Content -->
  <div class="relative z-10">
    <h1 class="text-3xl md:text-5xl font-bold mb-2 text-white">Aricio D. Bonina</h1>
    <p class="text-2xl">Real Estate Leasing</p>
  </div>
</section>

<style>
  /* Ensures the background image covers the entire section and the text stays centered */
  .h-screen {
    height: 100vh;
  }

  .custom-bg {
    background-image: url('/assets/Building1.jpg');
    background-size: cover; /* Ensures it covers the entire section */
    background-position: center; /* Center the image */
    width: 100%;
    height: 100%;
  }
</style>
