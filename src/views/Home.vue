<script setup>
</script>
<template>
  <div class="sm:hidden">
    <carousel :autoplay="4000" :wrap-around="true" :items-to-show="1">
      <slide v-for="(slide, index) in slides" :key="index">
        <img :src="'/' + slide + '.jpg'" alt="" />
      </slide>
      <!-- <template #addons>
        <navigation />
        <pagination />
      </template> -->
    </carousel>
    <div class="flex px-6 rocky justify-between">
      <div class="m-6 relative card">
        <img src="../assets/match.png" alt="" />
        <div class="relative z-30">
          <img class="ml-auto -mt-4" src="../assets/button.png" alt="" />
          <span class="absolute top-3 right-8 text-xl">Sports</span>
        </div>
        <div class="container">
          <div class="w-full overlay bg-black opacity-50 absolute top-0"></div>
          <button
            class="uppercase p-4 text-center button absolute text-[#ebc86d]"
          >
            play for sports
          </button>
        </div>
      </div>
      <div class="m-6 relative card">
        <img src="../assets/entertainment.png" alt="" />
        <div class="relative z-30">
          <img class="ml-auto -mt-4" src="../assets/button.png" alt="" />
          <span class="absolute top-3 right-4 text-xl">Live Casino</span>
        </div>
        <div class="container">
          <div class="w-full overlay bg-black opacity-50 absolute top-0"></div>
          <button
            class="uppercase p-4 text-center button absolute text-[#ebc86d]"
          >
            play for live
          </button>
        </div>
      </div>
      <div class="m-6 relative card">
        <img src="../assets/electronic.png" alt="" />
        <div class="relative z-30">
          <img class="ml-auto -mt-4" src="../assets/button.png" alt="" />
          <span class="absolute top-3 right-4 text-xl">E-Games</span>
        </div>
        <div class="container">
          <div class="w-full overlay bg-black opacity-50 absolute top-0"></div>
          <button
            class="uppercase p-4 text-center button absolute text-[#ebc86d]"
          >
            play for games
          </button>
        </div>
      </div>
      <div class="m-6 relative card">
        <img src="../assets/animal.png" alt="" />
        <div class="relative z-30">
          <img class="ml-auto -mt-4" src="../assets/button.png" alt="" />
          <span class="absolute top-3 right-2 text-xl">Chess games</span>
        </div>
        <div class="container">
          <div class="w-full overlay bg-black opacity-50 absolute top-0"></div>
          <button
            class="uppercase p-4 text-center button absolute text-[#ebc86d]"
          >
            play for chess
          </button>
        </div>
      </div>
    </div>

    <div class="flex justify-between p-6 ml-10">
      <div class="another">
        <div
          class="
            flex
            bg-black
            text-white
            hover:text-[#e17f00] hover:bg-gray-700
            p-4
          "
        >
          <img class="w-44" src="../assets/right-top.png" alt="" />
          <div class="my-auto ml-10">
            <div class="text-4xl uppercase">mg slot</div>
            <span>E-Games</span>
          </div>
        </div>
        <div
          class="
            flex
            bg-black
            text-white
            hover:text-[#e17f00] hover:bg-gray-700
            p-4
            my-2
          "
        >
          <img class="w-44" src="../assets/jdb.png" alt="" />
          <div class="my-auto ml-10">
            <div class="text-4xl uppercase">jdb slot</div>
            <span>E-Games</span>
          </div>
        </div>
      </div>
      <div>
        <img src="../assets/banner.png" alt="" />
        <div class="text-center my-8">
          <button class="p-4 text-center button w-72 text-[#ebc86d]">
            Bet now
          </button>
        </div>
      </div>
    </div>

    <div class="live-bg">
      <div class="flex justify-evenly">
        <div class="w-80">
          <img src="../assets/rw.png" alt="" />
        </div>
        <div class="flex w-2/3 flex-wrap">
          <div
            class="single weird text-center text-gray-400 hover:text-[#e17f00]"
          >
            <div class="py-28">
              <div class="uppercase text-4xl">Ae live</div>
              <span class="text-lg">Live casino</span>
            </div>
          </div>
          <div class="single text-center text-gray-400 hover:text-[#e17f00]">
            <div class="py-28">
              <div class="uppercase text-4xl">Ae live</div>
              <span class="text-lg">Live casino</span>
            </div>
          </div>
          <div
            class="single weird text-center text-gray-400 hover:text-[#e17f00]"
          >
            <div class="py-28">
              <div class="uppercase text-4xl">Ae live</div>
              <span class="text-lg">Live casino</span>
            </div>
          </div>
          <div class="single text-center text-gray-400 hover:text-[#e17f00]">
            <div class="py-28">
              <div class="uppercase text-4xl">Ae live</div>
              <span class="text-lg">Live casino</span>
            </div>
          </div>
          <div
            class="single weird text-center text-gray-400 hover:text-[#e17f00]"
          >
            <div class="py-28">
              <div class="uppercase text-4xl">Ae live</div>
              <span class="text-lg">Live casino</span>
            </div>
          </div>
          <div class="single text-center text-gray-400 hover:text-[#e17f00]">
            <div class="py-28">
              <div class="uppercase text-4xl">Ae live</div>
              <span class="text-lg">Live casino</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="lg:hidden">
    <carousel :autoplay="4000" :wrap-around="true" :items-to-show="1">
      <slide v-for="(slide, index) in slides" :key="index">
        <img :src="'/mobile/' + slide + '.jpg'" alt="" />
      </slide>
      <!-- <template #addons>
        <navigation />
        <pagination />
      </template> -->
    </carousel>
    <div class="text-[#ebd193] bg-[#303032] rounded-md p-1 m-2">
      <div class="text-base px-2">Hot Game</div>
      <div class="flex justify-between m-2">
        <div class="m-1">
          <img class="w-20 rounded-md" src="/mobile/game1.png" alt="" />
        </div>
        <div class="m-1">
          <img class="w-20 rounded-md" src="/mobile/game2.png" alt="" />
        </div>
        <div class="m-1">
          <img class="w-20 rounded-md" src="/mobile/game3.png" alt="" />
        </div>
        <div class="m-1">
          <img class="w-20 rounded-md" src="/mobile/game4.png" alt="" />
        </div>
        <div class="m-1">
          <img class="w-20 rounded-md" src="/mobile/game5.png" alt="" />
        </div>
      </div>
    </div>
    <div class="bg-[#303032] rounded-md p-1 m-2">
      <div class="flex">
        <div class="p-2 flex w-1/2">
          <img class="w-8 h-8 m-3" src="../assets/icons/user.png" alt="" />
          <div>
            <span class="text-gray-500 text-sm">Welcome</span> <br />
            <span class="text-[#ebd193] text-sm">Please Login !</span>
          </div>
        </div>
        <div class="w-1/2 text-sm text-gray-500 px-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </div>
      </div>

      <div class="flex relative h-[400px] scrol">
        <div class="w-20 fixed left-0 p-2">
          <div class="m-1">
            <img src="../assets/icons/live.png" alt="" />
          </div>
          <div class="m-1">
            <img src="../assets/icons/sport.png" alt="" />
          </div>
          <div class="m-1">
            <img src="../assets/icons/lottery.png" alt="" />
          </div>
          <div class="m-1">
            <img src="../assets/icons/poker.png" alt="" />
          </div>
          <div class="m-1">
            <img src="../assets/icons/used.png" alt="" />
          </div>
          <div class="m-1">
            <img src="../assets/icons/game.png" alt="" />
          </div>
        </div>
        <div class="w-20"></div>
        <div class="w-full">
          <div v-for="img in 9" :key="img">
            <img
              class="rounded-md my-2"
              :src="'/mobile/img' + img + '.png'"
              alt=""
            />
          </div>
        </div>
      </div>

      <div
        class="
          fixed
          bg-[#303032]
          w-[89%]
          justify-between
          flex
          rounded-full
          bottom-3
          p-4
        "
      >
        <div>
          <img class="w-6" src="../assets/icons/ho_ho1@3x.png" alt="" />
        </div>
        <div>
          <img class="w-6" src="../assets/icons/ho_ac2@3x.png" alt="" />
        </div>
        <div>
          <img class="w-6" src="../assets/icons/ho_wa2@3x.png" alt="" />
        </div>
        <div>
          <img class="w-6" src="../assets/icons/ho_co2@3x.png" alt="" />
        </div>
        <div>
          <img class="w-6" src="../assets/icons/ho_my2@3x.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
// If you are using PurgeCSS, make sure to whitelist the carousel CSS classes
import "vue3-carousel/dist/carousel.css";
import { Carousel, Slide, Pagination, Navigation } from "vue3-carousel";

export default {
  name: "App",
  components: {
    Carousel,
    Slide,
    Pagination,
    Navigation,
  },
  data() {
    return {
      slides: ["slide1", "slide2"],
    };
  },
};
</script>

<style scoped>
.rocky {
  background-image: url("../assets/rocky-bg.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.live-bg {
  background-image: url("../assets/live-bg.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.overlay {
  height: 330px;
}
.button {
  background-image: url("../assets/hmmm.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  top: 150px;
  left: 50px;
}
.single:hover {
  background-image: url("../assets/hover.png");
}
.container {
  display: none;
}

.card:hover .container {
  display: block;
}
.another {
  width: 500px;
}
.weird {
  background-image: url("../assets/bg-small.png");
}
.single {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 300px;
  width: 300px;
}
.scrol {
  overflow: auto;
}
</style>