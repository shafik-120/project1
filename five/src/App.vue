<script setup>
  const images = [
    {
      src: 'https://cdn.pixabay.com/photo/2018/01/12/10/19/fantasy-3077928_1280.jpg',
      title: 'woman in white dress standing on rock',
      alt: 'woman in white dress standing on rock'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2014/02/27/16/10/flowers-276014_1280.jpg',
      title: 'Use this photo to create a free design',
      alt: 'Use this photo to create a free design'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2015/12/01/20/28/forest-1072828_1280.jpg',
      title: 'green trees on brown grass field during daytime',
      alt: 'green trees on brown grass field during daytime'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885_1280.jpg',
      title: 'silhouette of tree near body of water during beautiful sunset',
      alt: 'silhouette of tree near body of water during beautiful sunset'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2015/12/01/20/28/road-1072823_1280.jpg',
      title: 'The internet has provided users with an endless',
      alt: 'The internet has provided users with an endless'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2013/11/28/10/36/road-220058_1280.jpg',
      title: 'where Frequently Asked Questions',
      alt: 'where Frequently Asked Questions'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2014/04/14/20/11/pink-324175_1280.jpg',
      title: 'pink petaled flowers',
      alt: 'pink petaled flowers'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2017/05/08/13/15/spring-bird-2295434_1280.jpg',
      title: 'I am a portrait photographer in Michigan',
      alt: 'I am a portrait photographer in Michigan'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2016/01/08/11/57/butterflies-1127666_1280.jpg',
      title: 'two gray butterflies on yellow flowers',
      alt: 'two gray butterflies on yellow flowers'
    },
    {
      src: 'https://cdn.pixabay.com/photo/2017/02/08/17/24/fantasy-2049567_1280.jpg',
      title: 'An FAQ generator is a tool that creates',
      alt: 'An FAQ generator is a tool that creates'
    },
    
  ]

import { ref, reactive } from 'vue'
let count = ref(3)

function nextImg (){ 
  if ( count.value == images.length - 1) {
    count.value = 0;
  } else {
    count.value++
  }
  console.log(count.value)
} 
function prevImg (){
  if (count.value == 0) {
    count.value = images.length - 1
  } else {
    count.value--
  }
  console.log(count.value)
}

function allImgFn(index){
  count.value = index
  console.log(index);

}
</script>

<template>
  <div class="carosul">
    <div class="slider flex">
      <div class="btn">
        <button @click="prevImg">Prev</button>
      </div>
      <div class="silderAllImg">
        <div class="ImageAll">
          <img :src="images[count].src" alt="" class="allimages">
        </div>
        <div class="flex overFlw gap">
          <img @click="allImgFn(index)" :src="image.src" alt="" v-for="(image, index) in images" :key="index" class="nextImg">
        </div>
      </div>
      <div class="btn">
        <button @click="nextImg">Next</button>
      </div>
    </div>
  </div>
</template>

<style scoped> 
.gap{
  gap: 8px;
}
.overFlw{
  width: 100%;
  overflow: hidden;
}
.nextImg{
  width: 100px;
  height: 50px;
}
.ImageAll{
  width: 100%;
  height: 40rem;
  overflow: hidden;
  margin: 10px 0;
}
img{
  max-width: 100%;
  transition: transform 0.7s ease-in-out;
  cursor: pointer;
}
img:hover{
  transform: scale(1.4);
}
.flex{
  display: flex;
}
button{
  margin: 0 6px;
  margin-top: 40ex;
  border: 2px double rebeccapurple;
  border-radius: 6px ;
  padding: 10px 30px;
  cursor: pointer;
}
</style>
