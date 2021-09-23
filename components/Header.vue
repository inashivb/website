
<template>
    <header>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <div class="h-full bg-gray-700 font-extrabold flex flex-col md:flex-row shadow-lg">
            <div v-if="false" class="text-gray-100 text-center p-7">Hello!</div>
            <nuxt-link to="/" class="menu-item">
               <div class="fa fa-home center w3-large"></div>
            </nuxt-link>
            <nuxt-link to="/about" class="menu-item">
               <label>About</label> 
            </nuxt-link>
            <nuxt-link to="/blog" class="menu-item">
                Blog
            </nuxt-link>
            <nuxt-link to="/clickme" class="menu-item">
                Click me
            </nuxt-link>
        </div>
        <div class="px-28">
            <div class="arrow-up md:float-right"></div>
        </div>
    </header>
</template>

<style>
.menu-item {
    @apply p-7 flex-auto block text-center h-full text-gray-200 hover:bg-gray-400
}
.arrow-up {
    width: 0; 
    height: 0;  
    border-left: 20px solid transparent;
    border-right: 20px solid transparent; 
    border-bottom: 20px solid rgb(248, 135, 5);
    animation: bounce 0.7s;
    animation-direction: alternate;
    animation-iteration-count: infinite;
}
@keyframes bounce {
  from { transform: translate3d(0, 0, 0);     }
  to   { transform: translate3d(0, 30px, 0); }
}
</style>