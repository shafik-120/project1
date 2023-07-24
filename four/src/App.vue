<script setup>
// import carosul from './components/carosul.vue'
import myChange from './components/myChange.vue';
// import { ref } from 'vue';

// const currentIndex = ref(0);

// function prevImg() {
//   currentIndex.value = (currentIndex.value - 1 + images.length) % images.length;
// }

// function nextImg() {
//   currentIndex.value = (currentIndex.value + 1) % images.length;
// }

// const images = [
//   'https://cdn.pixabay.com/photo/2023/07/19/17/21/chrysanthemum-8137432_1280.jpg',
//   'https://cdn.pixabay.com/photo/2023/07/18/15/17/large-headed-knapweed-8135055_1280.jpg',
//   'https://cdn.pixabay.com/photo/2023/07/17/13/44/prairie-dog-8132681_1280.jpg',
//   'https://cdn.pixabay.com/photo/2023/07/18/15/17/large-headed-knapweed-8135055_1280.jpg',
//   'https://cdn.pixabay.com/photo/2023/07/17/13/44/prairie-dog-8132681_1280.jpg',
//   'https://cdn.pixabay.com/photo/2023/07/17/13/50/baby-snow-leopard-8132690_1280.jpg',
//   'https://cdn.pixabay.com/photo/2023/07/18/15/17/large-headed-knapweed-8135055_1280.jpg',
//   'https://cdn.pixabay.com/photo/2023/07/19/17/21/chrysanthemum-8137432_1280.jpg',
//   'https://media.istockphoto.com/id/1391434319/photo/picturesque-mountain-valley-on-a-sunny-summer-day-river.webp?b=1&s=612x612&w=0&k=20&c=waY9538hswrdkHUC566Ah0OO3OwiHX6dX6avAejtVBY=',
// ];
</script>

<template>
  <myChange/>
  <!-- <carosul/> -->
  <!-- <div>
    <div class="flex">
      <div class="btn w-1/6">
        <button @click="prevImg" class="border-2 border-gray-300 rounded-md shadow-indigo-300 shadow-md">Prev</button>
      </div>

      <div class="text-center bg-slate-100 relative h-[35rem] overflow-hidden">
        <div v-for="(image, index) in images" :key="index" class="absolute w-full h-full allImg" v-show="index === currentIndex">
          <div class="">
            <img :src="image" class="sobing w-full h-full" alt="">
          </div>
          <div class="translate-y-[-9rem] bg-[#8080807d] text-white p-5">
            <h4 class="font-bold text-xl capitalize">Demo Text The World</h4>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur neque nostrum quisquam! Nemo, labore adipisci a vitae at voluptas numquam.</p>
          </div>
        </div>
      </div>

      <div class="btn w-1/6">
        <button @click="nextImg" class="border-2 border-gray-300 rounded-md shadow-indigo-300 shadow-md">Next</button>
      </div>
    </div>
  </div> -->
</template>
<style scoped></style>