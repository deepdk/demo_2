<script>
    import "../app.css";
  </script>
  

<div class="flex flex-col min-h-screen">
  <nav class="text-black p-4" style="position: sticky; top: 0; z-index: 1000; background-image: linear-gradient(to right, #9BF8F4, #6F7BF7); font-family: 'Poppins', sans-serif;">
    <div class="container mx-auto flex justify-start items-center gap-x-8">
        <a class="text-xl" href="/">Deepali Kank</a>
        <div class="flex gap-8">
            <a class="hover:text-gray-300" href="/">Home</a>
            <a class="hover:text-gray-300" href="/about">About</a>
            <a class="hover:text-gray-300" href="/projects">Projects</a>
            <a class="hover:text-gray-300" href="https://deepdk.quarto.pub/deepalis-blog/">Blog</a>
        </div>
    </div>
    <div class="container mx-auto flex justify-end items-center gap-x-8 -mt-6">
      <!-- Social media icons -->
      <div class="flex gap-6">
        <!-- Replace href with your actual social media profile URLs -->
        <a href="https://www.linkedin.com/in/deepali-kank/" class="text-lg" aria-label="LinkedIn" target="_blank" rel="noopener noreferrer">
          <i class="fab fa-linkedin-in fa-1.5x"></i>
        </a>
        <a href="https://github.com/deepdk" class="text-lg" aria-label="GitHub" target="_blank" rel="noopener noreferrer">
          <i class="fab fa-github fa-1.5x"></i>
        </a>
        <a href="mailto:deepalikank1@gmail.com" class="text-lg" aria-label="Email">
          <i class="fas fa-envelope fa-1.5x"></i>
        </a>
        <a href="https://twitter.com/DeepaliKank" class="text-lg" aria-label="X">
          <i class="fas fa-x fa-1.5x"></i>
        </a>
      </div>
</nav>


<main class="flex-grow mb-10">
  <slot />
</main>

<footer class="text-black p-4" style="background-image: linear-gradient(to right, #9BF8F4, #6F7BF7); font-family: 'Poppins', sans-serif;">
  <div class="container mx-auto flex flex-col items-center gap-4">
    <!-- Social media icons -->
    <div class="flex gap-4">
      <!-- Replace href with your actual social media profile URLs -->
      <a href="https://www.linkedin.com/in/deepali-kank/" class="text-lg" aria-label="LinkedIn" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-linkedin-in fa-1.5x"></i>
      </a>
      <a href="https://github.com/deepdk" class="text-lg" aria-label="GitHub" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github fa-1.5x"></i>
      </a>
      <a href="mailto:deepalikank1@gmail.com" class="text-lg" aria-label="Email">
        <i class="fas fa-envelope fa-1.5x"></i>
      </a>
      <a href="https://twitter.com/DeepaliKank" class="text-lg" aria-label="X">
        <i class="fas fa-x fa-1.5x"></i>
      </a>
    </div>
    
    <!-- Copyright and other information -->
    <div class="text-center">
      <p>Copyright © 2024 Deepali Kank. All rights reserved.</p>
      <a href="/cookie-policy" class="text-black hover:text-gray-300">Cookie Preferences</a>
    </div>
  </div>
</footer>

</div>  

  
  
