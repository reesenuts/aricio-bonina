<script>
    let mobileMenuOpen = false;
  
    function toggleMobileMenu() {
      mobileMenuOpen = !mobileMenuOpen;
    }
  </script>
  
  <header class="flex items-center justify-between px-8 py-4 border-b border-gray-200">
    <!-- Logo Section -->
    <div class="text-2xl font-bold text-[#4D869C]">
      <a href="/">YourLogo</a>
    </div>
  
    <!-- Navigation Links for Desktop -->
    <nav class="hidden md:flex space-x-16 text-[#4D869C]">
      <a href="#home" class="hover:text-blue-600">Home</a>
      <a href="#about" class="hover:text-blue-600">About</a>
      <a href="#features" class="hover:text-blue-600">Features</a>
      <a href="#contact" class="hover:text-blue-600">Contact</a>
    </nav>
  
    <!-- Log In Button -->
    <div>
      <button class="border border-[#4D869C] px-4 py-1 rounded hover:bg-[#4D869C] hover:text-white transition-colors">
        Log In
      </button>
    </div>

     <!-- Mobile Menu Button 
    <div class="md:hidden">
        <button class="text-[#4D869C]" on:click={toggleMobileMenu}>
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
          </svg>
        </button>
      </div>
  
    Mobile Navigation Links 
    {#if mobileMenuOpen}
      <div class="absolute right-0 bg-white border border-gray-200 rounded-md shadow-md mt-2 w-48 md:hidden">
        <nav class="flex flex-col space-y-2 p-4 text-[#4D869C]">
          <a href="#home" class="hover:text-blue-600">Home</a>
          <a href="#about" class="hover:text-blue-600">About</a>
          <a href="#features" class="hover:text-blue-600">Features</a>
          <a href="#contact" class="hover:text-blue-600">Contact</a>
        </nav>
      </div>
    {/if} -->
  </header>
  