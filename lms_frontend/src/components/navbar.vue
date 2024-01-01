<template>


<nav class="bg-gray-800 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            
            <div>
                        
                        
                            <RouterLink to="/" class="flex items-center py-4 px-2">
                                <img src="../assets/logo.png" alt="Logo" class="h-12 w-12 mr-2 rounded-md">
                            </RouterLink>
                            
                    </div>
            

            <div class="hidden md:flex space-x-4">
                <RouterLink to="" class="hover:text-gray-300">Courses</RouterLink>
                <RouterLink to="" class="hover:text-gray-300">About Us</RouterLink>
                <RouterLink to="" class="hover:text-gray-300">Support</RouterLink>
                
            </div>

   
            <div class="space-x-4">
                <RouterLink to="/login" class="px-4 py-2 border border-transparent text-sm font-medium rounded-md text-gray-800 bg-white hover:bg-gray-100">Login</RouterLink>
                <RouterLink to="/sign-up" class="px-4 py-2 border border-transparent text-sm font-medium rounded-md text-white bg-blue-500 hover:bg-blue-600">Sign Up</RouterLink>
                
            </div>
        </div>
    </nav>






    <router-view/>
  </template>
  
  <style lang="scss">
  
  
  
  </style>


<script>


export default {
  name: 'navbar',
  
}
</script>