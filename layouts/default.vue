<template>
    <div>
        <header>
            <nav>
                <nuxt-link to="/">Maine</nuxt-link>
                <ul>
                   <li><nuxt-link to="/">Home</nuxt-link></li>
                   <li><nuxt-link to="/about">About</nuxt-link></li>
                   <li><nuxt-link to="/products">Products</nuxt-link></li>
                </ul>
                <a href="/about">normal link</a>
            </nav>
        </header>

        <!-- out the page content -->

        <div>
            <slot />
        </div>
      
    </div>
</template>

<script setup>

</script>
<style scoped>  
   .router-link-exact-active{
    color: aqua;
   }
</style>