<script setup>
import {ref, reactive} from 'vue'
const activeIndex = ref(0)

const carouselItems = [
  {
    image: 'https://cdn.pixabay.com/photo/2014/02/27/16/10/flowers-276014_640.jpg',
    title: 'First Slide Label',
    caption: 'Nulla vitae elit libero, a pharetra augue mollis interdum. Nulla vitae elit libero, a pharetra augue'
  },
  {
    image: 'https://cdn.pixabay.com/photo/2012/03/01/00/55/flowers-19830_640.jpg',
    title: 'Second Slide Label',
    caption: 'Nulla vitae elit libero, a pharetra augue mollis interdum.'
  },
  {
    image: 'https://cdn.pixabay.com/photo/2016/01/08/11/57/butterflies-1127666_640.jpg',
    title: 'Third Slide Label',
    caption: 'Nulla vitae elit libero, a pharetra augue mollis interdum.'
  },
  {
    image: 'https://cdn.pixabay.com/photo/2015/12/01/20/28/forest-1072828_640.jpg',
    title: 'Fourth Slide Label',
    caption: 'Nulla vitae elit libero, a pharetra augue mollis interdum.'
  },
  {
    image: 'https://cdn.pixabay.com/photo/2015/10/30/20/13/sunrise-1014712_640.jpg',
    title: 'Fifth Slide Label',
    caption: 'Nulla vitae elit libero, a pharetra augue mollis interdum.'
  }
]

const imageFilter = '-webkit-filter: grayscale(100%);filter: grayscale(100%);'
</script>

<template>
  <h4>Vue Image Carousel</h4>
  <ol class="carousel-thumnails">
    <img @click="activeIndex = index" height="50" :style="activeIndex != index?imageFilter:''" style="cursor: pointer;" class="mx-1" v-for="(thumnail, index) in carouselItems" :key="index" :src="thumnail.image" alt="">
    
  </ol>

  <div id="carouselExampleCaptions" class="carousel" data-ride="carousel">    
    <ol class="carousel-indicators">
      <li @click="activeIndex = index" data-target="#carouselExampleCaptions" v-for="(items, index) in carouselItems" :key="index" :class="index == activeIndex?'active':''"></li>
    </ol>
    
    <div class="carousel-inner">        
      <div class="carousel-item active">           
        <img height="500" :src="carouselItems[activeIndex].image" class="d-block w-100 img img-responsive" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>{{ carouselItems[activeIndex].title }}</h5>
          <p>{{ carouselItems[activeIndex].caption }}</p>
        </div>
      </div>  
    </div>    
    <a @click.prevent="0 == activeIndex ? activeIndex = (carouselItems.length) - 1 : activeIndex--" class="carousel-control-prev" href="#" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a @click.prevent="(carouselItems.length) - 1 == activeIndex ? activeIndex = 0 : activeIndex++" class="carousel-control-next" href="#" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
    
</template>

<style scoped></style>