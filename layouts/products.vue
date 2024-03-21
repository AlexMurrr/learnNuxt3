<template>
    <div>
        <header>
            <nav>
                <nuxt-link to="/products">Maine products</nuxt-link>
            </nav>
        </header>

        <!-- out the page content -->

        <div>
            <slot />
        </div>     
    <footer>
        <ul>
            <li><nuxt-link to="/">Home</nuxt-link></li>
            <li><nuxt-link to="/about">About</nuxt-link></li>
            <li><nuxt-link to="/products">Products</nuxt-link></li>
        </ul>
    </footer>    
    </div>
</template>

<script setup>
</script>

<style scoped>  
   .router-link-exact-active{
    color: aqua;
   }
</style>