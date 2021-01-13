<template>
    <nav class="shadow-md">
      <div class="flex flex-row justify-center md:justify-between items-center
      container mx-auto px-20 flex-wrap">
        <img :src="require('@/assets/img/smartct-logo-primary-tight.png')"
        width="189px" class="py-2" />
        <ul class="w-full max-w-screen-md py-4 lg:py-0 lg:pb-0 md:flex justify-between font-medium
        space-y-2 md:space-y-0 text-center md:text-left">
          <li>
            <router-link class="text-primary" to="/">Home</router-link>
          </li>
          <!--
          <li>
            <router-link class="text-primary" to="About">About</router-link>
          </li>
          <li>
            <a class="text-gray-900" href="#">Services</a>
          </li>
          <li>
            <a class="text-gray-900" href="#">Blog</a>
          </li>
          <li>
            <a class="text-gray-900" href="#">Data Portal</a>
          </li>
          -->
        </ul>
      </div>
    </nav>
</template>

<script>

export default {
  name: 'Navbar',
};
</script>
