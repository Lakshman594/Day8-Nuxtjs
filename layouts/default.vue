<template>

    <div>
    <!-- <p>Hii this is in default page</p> -->

    <nav class="bg-yellow-500  shadow-lg p-3 text-white text-lg flex justify-between text-rose-900">

    <nuxt-link to="/">Home</nuxt-link> &nbsp;
    <nuxt-link to="/about">About</nuxt-link>&nbsp;
    <nuxt-link to="/iphone">Iphones</nuxt-link>&nbsp;

    <nuxt-link to="/profile">profile</nuxt-link>

</nav>

    <slot />

</div>
</template>


<!-- <script>
import "assets/css/tailwind.css";
</script> -->