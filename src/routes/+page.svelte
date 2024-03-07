<script>
    let selectedImage = null;
  
    function selectImage(imageSrc) {
      selectedImage = imageSrc;
    }
  
    function deselectImage() {
      selectedImage = null;
    }
  </script>
    
    <main class="p-4">
      <!-- Home Section -->
      <section id="home" class="mt-10 flex items-center justify-center px-4 md:px-8">
        <div class="flex items-center justify-center space-x-8 max-w-4xl mx-auto">
          <!-- Profile Image -->
          <!-- svelte-ignore a11y-img-redundant-alt -->
          <img src="/profile.png" alt="Profile Image of Deepali Kank" class="rounded-full w-48 h-48 object-cover">
          <div>
            <h1 class="text-#6f7bf7 text-3xl" style="font-family: 'Poppins', sans-serif;">Data Visualization Specialist</h1>
            <p style="font-family: 'Roboto', sans-serif;">I'm a data analyst with a Master's in Statistics, passionate about turning data into compelling stories and visualizations. 
              I excel in crafting customized solutions to unlock data's full potential for businesses, prioritizing creativity and excellence. 
              Beyond data, I enjoy reading, learning new skills, and exploring my passions. 
              I'm eager to collaborate and bring your data to life.
            </p>
            <div class="flex space-x-6 mt-4" style="font-family: 'Poppins', sans-serif">
              <a href="https://calendly.com/deep_k/30min" class="text-black px-4 py-2 rounded inline-block text-center hover:font-semibold" style="background-image: linear-gradient(to right, #9BF8F4, #6F7BF7)">Schedule Call</a>
              <a href="mailto:deepalikank1@gmail.com" class="text-black px-4 py-2 rounded inline-block text-center hover:font-semibold" style="background-image: linear-gradient(to right, #9BF8F4, #6F7BF7)">Email Me</a>
              <a href="https://www.buymeacoffee.com/deepalik" class="text-black px-4 py-2 rounded inline-block text-center hover:font-semibold" style="background-image: linear-gradient(to right, #9BF8F4, #6F7BF7)">Support Me</a>
            </div>            
          </div>
        </div>
      </section>

      <div class="my-8 border-t border-gray-200"></div>      
    
      <!-- Projects Section -->
  <!-- Projects Section -->
  <section id="projects" class="text-center mt-8 px-4 md:px-8" style="font-family: 'Poppins', sans-serif">
    <h2 class="text-3xl">Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 mt-4">
      <!-- First project card with cover image -->
      <div class="border rounded-lg p-4 relative shadow-md">
        <!-- Image container with background cover -->
        <div class="bg-cover bg-center rounded-lg h-48 w-full" style="background-image: url('/survival.png');"></div>
        <div class="p-4 bg-white bg-opacity-75 rounded-lg">
          <h3 class="text-xl">Alone TV Series</h3>
          <p style="font-family: 'Roboto', sans-serif;">Beeswarm chart using Survival Data.</p>
          <a href="https://observablehq.com/d/51428880a530d5f8" style="color: #6f7bf7;"class="hover:underline">View Project</a>
        </div>
      </div>
      <!-- Second project card -->
      <div class="border rounded-lg p-4 relative shadow-md">
        <!-- Image container with background cover -->
        <div class="bg-cover bg-center rounded-lg h-48 w-full" style="background-image: url('/rladies.png');"></div>
        <div class="p-4 bg-white bg-opacity-75 rounded-lg">
          <h3 class="text-xl">Tribute to R Ladies</h3>
          <p style="font-family: 'Roboto', sans-serif;">An interactive data visualization of R Ladies events around the globe.</p>
          <a href="https://observablehq.com/d/d30791feffacf739" style="color: #6f7bf7;"class="hover:underline">View Project</a>
        </div>
      </div>
      <!-- Third project card -->
      <div class="border rounded-lg p-4 relative shadow-lg">
        <!-- Image container with background cover -->
        <div class="bg-cover bg-center rounded-lg h-48 w-full" style="background-image: url('/press.gif');"></div>
        <div class="p-4 bg-white bg-opacity-75 rounded-lg">
          <h3 class="text-xl">Press Freedom Index</h3>
          <p style="font-family: 'Roboto', sans-serif;">re-creation of the chart that was originally published in the The Guardian.</p>
          <a href="https://observablehq.com/d/c677d634f64c80ca" style="color: #6f7bf7;"class="hover:underline">View Project</a>
        </div>
      </div>
    </div>
  </section>

  <div class="my-8 border-t border-gray-200"></div>
  
  <!-- Visual Gallery Section -->
  <section id="visual-gallery" class="text-center mt-8 px-4 md:px-8" style="font-family: 'Poppins', sans-serif">
    <h2 class="text-center text-3xl">Visual Gallery</h2>
    <!-- svelte-ignore a11y-click-events-have-key-events -->
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-4 mt-4">
      <!-- Image 1 -->
  
      <!-- svelte-ignore a11y-click-events-have-key-events -->
      <!-- svelte-ignore a11y-img-redundant-alt -->
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/bill.png')}>
          <img class="object-cover w-full h-full" src="/bill.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
      
      <!-- svelte-ignore a11y-click-events-have-key-events -->
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/bob_ross.png')}>
          <!-- svelte-ignore a11y-img-redundant-alt -->
          <img class="object-cover w-full h-full" src="/bob_ross.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
      
      
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/chris.png')}>
          <!-- svelte-ignore a11y-img-redundant-alt -->
          <img class="object-cover w-full h-full" src="/chris.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/eurovision.png')}>
          <!-- svelte-ignore a11y-img-redundant-alt -->
          <img class="object-cover w-full h-full" src="/eurovision.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/ferris_wheel.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/ferris_wheel.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/friends.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/friends.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/gst.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/gst.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/hot_1.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/hot_1.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/hp_another_2.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/hp_another_2.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/human.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/human.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/lgbtq.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/lgbtq.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/membership.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/membership.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/pell_grants.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/pell_grants.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/taylor final.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/taylor final.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-click-events-have-key-events -->
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/votes for women_3.gif')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/votes for women_3.gif" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>
  
      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/yarn.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/yarn.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>

      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/R_egg_paint_figma.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/R_egg_paint_figma.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>

      <!-- svelte-ignore a11y-no-static-element-interactions -->
      <div class="gallery-item" on:click={() => selectImage('/portofig.png')}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class="object-cover w-full h-full" src="/portofig.png" alt="Description of image 1" style="aspect-ratio: 1 / 1;">
      </div>


  
  
  
      
      <!-- More images... -->
    </div>
  </section>
  
    
    
      <!-- Contact Section -->
      
    </main>
    
    <!-- Image Modal -->
  {#if selectedImage}
    <!-- svelte-ignore a11y-click-events-have-key-events -->
    <!-- svelte-ignore a11y-no-static-element-interactions -->
    <div class="modal" on:click={deselectImage}>
      <!-- svelte-ignore a11y-img-redundant-alt -->
      <img src={selectedImage} alt="Selected Image" class="modal-content">
    </div>
  {/if}
  
  <style>
    .gallery-item {
      cursor: pointer; /* Indicates the item is clickable */
      /* Other styles... */
    }
  
    .modal {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.8);
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 10; /* Ensure it's above other content */
    }
  
    .modal-content {
      max-width: 80%;
      max-height: 80%;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      transition: transform 0.25s ease;
    }
  
    /* Close the modal when clicking on the (semi-transparent) background */
    .modal:after {
      content: "✖";
      position: absolute;
      top: 20px;
      right: 30px;
      font-size: 30px;
      color: white;
      cursor: pointer;
    }

    </style>