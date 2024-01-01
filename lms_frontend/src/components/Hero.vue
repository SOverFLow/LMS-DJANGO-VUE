<template>


<section class="bg-gray-100 text-gray-800">
    <div class="container mx-auto px-6 py-20">
        <div class="flex flex-wrap items-center">
            <!-- Text-based content -->
            <div class="w-full md:w-1/2">
                <h2 class="text-4xl font-bold mb-2">Enhance Your Skills with Our Interactive Learning Platform</h2>
                <h3 class="text-2xl mb-8">Join thousands of learners and start your journey today!</h3>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Get Started</button>
            </div>

            <!-- Image or graphical content -->
            <div class="w-full md:w-1/2 text-center">
                <img class="inline-block mt-6 md:mt-0" src="../assets/hero.svg" alt="Learning Illustration">
            </div>
        </div>
    </div>
</section>
    
    
    
    
    
    
        <router-view/>
      </template>
      
      <style lang="scss">
      
      
      
      </style>
    
    
    <script>
    
    
    export default {
      name: 'Hero',
      
    }
    </script>