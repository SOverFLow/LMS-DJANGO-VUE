<template>
  
    <navbar/>
    <div class="mx-auto w-full max-w-md mt-40 mb-10">
            <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
                <h1 class="text-xl mb-5 text-center text-gray-700 font-bold">Login</h1>

                <div class="mb-4">
                    <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="Username">
                </div>

                <div class="mb-4">
                    <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="password" type="password" placeholder="Password">
                </div>

                

                <div class="flex items-center justify-between">
                    <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="submit">
                        Login
                    </button>
                </div>
            </form>
        </div>
    
  
  
  
  
  
  
  
  
  
  
  
  </template>
  
  <script>
  
  import navbar from '@/components/navbar.vue';
  
  
  export default {
      name: 'LoginView',
      components: { navbar}
  }
  </script>
  