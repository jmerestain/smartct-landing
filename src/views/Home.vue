<template>
  <div class="home">
    <section class="flex flex-row py-5 items-center lg:justify-between
    lg:flex-no-wrap flex-wrap justify-center container mx-auto lg:px-20 px-10">
      <div class="flex flex-col justify-center lg:justify-between">
        <h1 class="text-5xl font-medium select-none text-center md:text-left">
          Welcome to
        </h1>
        <img class="object-scale-down"
        :src="require('@/assets/img/smartct-colored.svg')" />
      </div>
      <div class="p-2">
        <img class="object-scale-down" :src="require('@/assets/img/rafiki.png')" />
      </div>
    </section>
    <section class="flex flex-row py-16 items-start lg:justify-between justify-center
    lg:space-y-0 space-y-8 lg:flex-no-wrap justify-center flex-wrap lg:space-x-4
    container mx-auto lg:px-20 px-5">
      <!--
      <div class="flex flex-col space-y-3 max-w-sm">
        <h2 class="text-center text-primary text-2xl font-medium">
          SmartCT Pilot Program
        </h2>
        <p class="px-2">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit,
          sed do eiusmod tempor incididunt ut labore et dolore magna
          aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
          Duis aute irure dolor in reprehenderit in voluptate velit
          esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
          occaecat cupidatat non proident, sunt in culpa qui officia
          deserunt mollit anim id est laborum.
        </p>
        <a class="text-secondary text-right font-medium" href="#">
          Learn More
        </a>
      </div>
      <div class="flex flex-col space-y-3 max-w-sm">
        <h2 class="text-center text-primary text-2xl font-medium">
          SmartCT Data Portal
        </h2>
        <p class="px-2">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit,
          sed do eiusmod tempor incididunt ut labore et dolore magna
          aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
          Duis aute irure dolor in reprehenderit in voluptate velit
          esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
          occaecat cupidatat non proident, sunt in culpa qui officia
          deserunt mollit anim id est laborum.
        </p>
        <a class="text-secondary text-right font-medium" href="#">
          Learn More
        </a>
      </div>
      -->
      <div class="flex flex-col space-y-3 max-w-sm">
        <h2 class="text-center text-primary text-2xl font-medium">
          Free Online Assessment
        </h2>
        <p class="px-2">
          Where is the future of your city heading?
          Are you duplicating effort and wasting resources?
          Do you know the value standards can bring?
          To find out the “Smartness” of your city and community, use our
          SmartCT Assessment for free! You can plot your overall maturity
          score in the city maturity model and the results for the individual
          city categories can be marked in the radar diagram.
        </p>
        <div class="flex justify-end">
          <a class="text-secondary text-right font-bold p-2 rounded-lg
          border-2 border-gray-600" href="https://assess.smartct.org">
            Learn More
          </a>
        </div>
      </div>
      <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FSmartCTorg&tabs=timeline&width=340&height=500&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=false&appId" width="340" height="500" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe>
      <Timeline id="smartctorg" sourceType="profile" :options="{ theme: 'dark', tweetLimit: '1' }"/>
    </section>
    <section class="bg-primary py-20">
      <div class="lg:container lg:mx-auto flex scrolling-auto pb-5 overflow-y-visible
      lg:justify-between lg:px-20 space-x-6 overflow-x-auto mx-5">
        <div class="card bg-white rounded-lg max-w-xs p-4 flex flex-col shadow-md flex-shrink-0
        justify-center">
          <h2 class="text-xl text-center font-medium py-2">
            SmartCT Plans
          </h2>
          <p class="mt-4">
            SmartCT jumpstarts and future-proofs smart cities with the proper use of technology
            and urban planning to assist government units with management and data analysis.
          </p>
        </div>
        <div class="card bg-white rounded-lg max-w-xs p-4 flex flex-col shadow-md flex-shrink-0
        justify-center">
          <h2 class="text-xl text-center font-medium py-2">
            SmartCT Data Portal
          </h2>
          <p class="mt-4">
            SmartCT's open data portal allows researchers to collaborate and create better
            data-driven solutions using data collected through the SmartCT network.
          </p>
        </div>
        <div class="card bg-white rounded-lg max-w-xs p-4 flex flex-col
        shadow-md flex-shrink-0 justify-center">
          <h2 class="text-xl text-center font-medium py-2">
            SmartCT Hall
          </h2>
          <p class="mt-4">
            Discuss with your peers to better understand possible policies and practices
            and pinpoint issues within communities.
          </p>
        </div>
      </div>
    </section>
    <section class="bg-white flex flex-col py-10 container mx-auto lg:px-20 px-5 pb-16">
      <h2 class="text-2xl font-medium text-center mt-4 mb-10 font-bold">
        Partner Organizations
      </h2>
      <div class="flex flex-row justify-center lg:justify-between mb-2 flex-wrap">
        <img class="p-4 flex-shrink-0" :src="require('@/assets/img/partners/1 1.png')" />
        <img class="p-4 flex-shrink-0" :src="require('@/assets/img/partners/1 2.png')" />
        <img class="p-6 flex-shrink-0" :src="require('@/assets/img/partners/1 3.png')" />
      </div>
      <div class="flex flex-row justify-center lg:justify-between mb-2 flex-wrap">
        <img class="p-4 flex-shrink-0" :src="require('@/assets/img/partners/2 1.png')" />
        <img class="p-4 flex-shrink-0" :src="require('@/assets/img/partners/2 2.png')" />
        <img class="p-4 flex-shrink-0" :src="require('@/assets/img/partners/2 3.png')" />
      </div>
      <div class="flex flex-row justify-center lg:justify-between mb-2 flex-wrap">
        <img class="flex-shrink-0 flex-grow-0 w-48 h-48"
          :src="require('@/assets/img/partners/3 1.png')" />
        <img class="flex-shrink-0 flex-grow-0 w-48 h-48"
          :src="require('@/assets/img/partners/3 3.png')" />
        <img class="flex-shrink-0 flex-grow-0 w-48 h-48"
          :src="require('@/assets/img/partners/3 2.png')" />
        <img class="flex-shrink-0 flex-grow-0 w-48 h-48"
          :src="require('@/assets/img/partners/3 4.png')" />
      </div>
      <div class="flex flex-col justify-center mt-20 p-10 bg-primary rounded-lg">
        <p class="text-2xl text-white text-center">Partner with SmartCT</p>
        <a href="mailto://info@smartct.org">
          <p class="text-center text-white">
            info@smartct.org
          </p>
        </a>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
import { Timeline } from 'vue-tweet-embed';

export default {
  name: 'Home',
  components: {
    Timeline,
  },
};
</script>

<style>
  .card {
    height: 20rem;
  }
</style>
