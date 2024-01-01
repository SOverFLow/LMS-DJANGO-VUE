<template>


   
        
<section class="bg-white text-gray-800 py-20">
    <div class="container mx-auto px-6 text-center">
        <h2 class="text-4xl font-bold mb-10">Our Services</h2>

        <div class="flex flex-wrap justify-center">
            <!-- Service 1 -->
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div class="text-6xl text-blue-500">
                    <i class="fas fa-chalkboard-teacher"></i>
                </div>
                <h3 class="text-xl font-semibold my-4">Interactive Courses</h3>
                <p>Engage in a variety of courses with interactive content to enhance your learning experience.</p>
            </div>

            <!-- Service 2 -->
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div class="text-6xl text-green-500">
                    <i class="fas fa-users"></i>
                </div>
                <h3 class="text-xl font-semibold my-4">Community Support</h3>
                <p>Join a community of learners and educators to share knowledge and resources.</p>
            </div>

            <!-- Service 3 -->
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div class="text-6xl text-red-500">
                    <i class="fas fa-award"></i>
                </div>
                <h3 class="text-xl font-semibold my-4">Certification</h3>
                <p>Earn certificates as you complete courses to showcase your skills and knowledge.</p>
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
          name: 'Services',
          
        }
        </script>