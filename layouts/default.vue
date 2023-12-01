<template>
    <div class="px-6 py-3 flex font-sans text-3xl text-white justify-between bg-black text-white h-full border-2 border-amber-900">
        <div >
        <NuxtLink to="/" >
             Home
        </NuxtLink>
          
        <NuxtLink to="/blog" class="px-3 py-3" > 
            Blog
        </NuxtLink>
           
        <NuxtLink to="/tipstricks" class="px-3 py-3"> 
            Tips&Tricks
        </NuxtLink>
        </div>
        
         <div>
        <NuxtLink to="/about" class="px-3 py-3">
            About
        </NuxtLink>
         </div>

       
           
    </div>
    <slot/>

</template>