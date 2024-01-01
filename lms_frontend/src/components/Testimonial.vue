<template>

<section class="bg-gray-100 text-gray-800 py-20">
    <div class="container mx-auto px-6 text-center">
        <h2 class="text-4xl font-bold mb-10">What Our Users Say</h2>

        <div class="flex flex-wrap justify-center">
            <!-- Testimonial 1 -->
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <p class="italic">"The courses are comprehensive and engaging. I've learned so much in just a few months!"</p>
                    <div class="mt-4">
                        <p class="font-semibold">Jane Doe</p>
                        <p class="text-sm text-gray-600">Web Developer</p>
                    </div>
                </div>
            </div>

            <!-- Testimonial 2 -->
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <p class="italic">"Thanks to this platform, I've gained skills that have significantly advanced my career."</p>
                    <div class="mt-4">
                        <p class="font-semibold">John Smith</p>
                        <p class="text-sm text-gray-600">Data Analyst</p>
                    </div>
                </div>
            </div>

            <!-- Testimonial 3 -->
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <p class="italic">"I love the community aspect. It's great to learn and grow with others who share the same interests."</p>
                    <div class="mt-4">
                        <p class="font-semibold">Emily Johnson</p>
                        <p class="text-sm text-gray-600">Graphic Designer</p>
                    </div>
                </div>
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
          name: 'Testimonial',
          
        }
        </script>