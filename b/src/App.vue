<script setup>

const four_section_p = 'Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts.'

const carosulp = '“Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. ”'
const priceFastp = 'There live the blind texts'
const priceSecondp = 'Far far away behind the word'
const priceThredp = 'Far from the countries Vokalia and Consonantia'
</script>

<template>
  <section class="menu">
  <div class="navbar flex">
    <img class="w-20 h-20" src="https://bloggytalky.com/wp-content/uploads/2017/07/create-a-free-logo-design-logo-designs-design-a-free-logo-design-a-free-logo-alltech-just-free-logo-design.png" alt="logo">
    <ul >
      <li class="inline-block ml-2"><a href="#">Home</a></li>
      <li class="inline-block ml-2"><a href="#">Service</a></li>
      <li class="inline-block ml-2"><a href="#">Blog</a></li>
      <li class="inline-block ml-2"><a href="#">Portfolio</a></li>
      <li class="inline-block ml-2"><a href="#">About</a></li>
    </ul>
  </div>
  </section>
  <section class="h">
    <div class="hero text-center py-8">
    <h1 class="text-6xl capitalize my-4">Build Your Amazing Website.</h1>
    <p class="font-bold text-white text-2xl">Designed with passion and coded to perfection.</p>
    <button class="text-white font-bold py-3 rounded-md px-20 border border-4 capitalize my-5">get start</button>
    <p class="text-white font-semibold text-2xl">Wondering how it works? <a href="#" class="text-blue-600 font-normal">Watch a video</a></p>
  </div>
  </section>
  <section class="secondSec flex ">
    <div class="">
      <p class="text-blue-400 uppercase"> digital services</p>
      <h3 class="text-3xl font-normal capitalize">selling digital service</h3>
      <p class="font-thin text-sm">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast</p>
      <ul class="list-disc">
        <li class="font-thin">There live the blind texts</li>
        <li class="font-thin">Far far away behind the word</li>
      </ul>
      <em class="font-sm font-thin">“Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. ”</em>
    </div>
    <div class="">
      <img src="http://nunforest.com/kinetic/images/dev8.png" alt="">
    </div>
  </section>


  <section class="thred flex">
    
    <div class="fastSec_img">
      <img class="" src="https://preview.colorlib.com/theme/launch/images/dashboard.jpg" alt="">
      <img class="hidden" src="https://preview.colorlib.com/theme/launch/images/dashboard.jpg" alt="">
      <img class="hidden" src="https://preview.colorlib.com/theme/launch/images/dashboard.jpg" alt="">
      <img class="hidden" src="https://preview.colorlib.com/theme/launch/images/dashboard.jpg" alt="">
    </div>
    <div class="secondSec_text">
      <div class="flex">
      <a href="#"><img src="" alt="fa"></a>
      <div class="">
        <h3>Grow Your Business</h3>
        <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
      </div>
    </div>
    <div class="flex">
      <a href="#"><img src="" alt="fa"></a>
      <div class="">
        <h3>Build Products</h3>
        <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
      </div>
    </div> 
    <div class="flex">
      <a href="#"><img src="" alt="fa"></a>
      <div class="">
        <h3>Success Every Day</h3>
        <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
      </div>
    </div> 
    <div class="flex">
      <a href="#"><img src="" alt="fa"></a>
      <div class="">
        <h3>Bring Ideas to Life</h3>
        <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
      </div>
    </div> 
    </div>

  </section>

  <section class="fourSection">
    <div class="text-start">
      <img src="" alt="ff">
      <h3>Grow Your Business</h3>
      <p>{{ four_section_p }}</p>
    </div>
    <div class="text-start">
      <img src="" alt="ff">
      <h3>Build Products</h3>
      <p>{{ four_section_p }}</p>
    </div>
    <div class="text-start">
      <img src="" alt="ff">
      <h3>Success Every Day</h3>
      <p>{{ four_section_p }}</p>
    </div>
    <div class="text-start">
      <img src="" alt="ff">
      <h3>Bring Ideas to Life</h3>
      <p>{{ four_section_p }}</p>
    </div>
  </section>

  <section class="fiveSecion">
    <div class="text-center">
      <h3 class="text-3xl capitalize">pricing</h3>
      <p class="">Pricing for everyone. Choose your plan now!</p>
    </div>

    <div class="flex">
      <div class="text-center bg-slate-300 rounded shadow shadow-md shadow-indigo-200 p-3 m-4">
      <h3 class="capitalize">free</h3>
      <p><sup>$</sup>0</p>
      <ul>
        <li>{{ priceFastp }}</li>
        <li>{{ priceSecondp }}</li>
        <li>{{ priceThredp }}</li>
      </ul>
      <button><a href="#" class="uppercase text-indigo-600 border border-2 py-3 px-10 rounded-lg">get started</a></button>
    </div>

    <div class="text-center bg-slate-300 rounded shadow shadow-md shadow-indigo-200 p-3 m-4">
      <h3 class="capitalize">Standard</h3>
      <p><sup>$</sup>19.99</p>
      <ul>
        <li>{{ priceFastp }}</li>
        <li>{{ priceSecondp }}</li>
        <li>{{ priceThredp }}</li>
      </ul>
      <button><a href="#" class="uppercase text-indigo-600 border border-2 py-3 px-10 rounded-lg">get started</a></button>
    </div>

    <div class="text-center bg-slate-300 rounded shadow shadow-md shadow-indigo-200 p-3 m-4">
      <h3 class="capitalize">Premium</h3>
      <p><sup>$</sup>79.99</p>
      <ul>
        <li>{{ priceFastp }}</li>
        <li>{{ priceSecondp }}</li>
        <li>{{ priceThredp }}</li>
      </ul>
      <button><a href="#" class="uppercase text-indigo-600 border border-2 py-3 px-10 rounded-lg">get started</a></button>
    </div>
    </div>
  </section>

  <section class="sixSection">
    <div class="text-center">
      <h2 class="text-3xl ">Advantage of using our products</h2>
      <p>Far from the countries Vokalia and Consonantia</p>
    </div>

    <div class="flex">
      <div class="flex">
        <img src="" alt="ff">
        <div class="">
          <h2>Grow Your Business</h2>
          <p>{{ four_section_p }}</p>
          <a href="#" class="font-normal text-sm text-blue-600 capitalize">learn more</a>
        </div>
      </div>
      <div class="flex">
        <img src="" alt="ff">
        <div class="">
          <h2>Build Products</h2>
          <p>{{ four_section_p }}</p>
          <a href="#" class="font-normal text-sm text-blue-600 capitalize">learn more</a>
        </div>
      </div>
    </div>

    <div class="flex">
      <div class="flex">
        <img src="" alt="ff">
        <div class="">
          <h2>Success Every Day</h2>
          <p>{{ four_section_p }}</p>
          <a href="#" class="font-normal text-sm text-blue-600 capitalize">learn more</a>
        </div>
      </div>
      <div class="flex">
        <img src="" alt="ff">
        <div class="">
          <h2>Bring Ideas to Life</h2>
          <p>{{ four_section_p }}</p>
          <a href="#" class="font-normal text-sm text-blue-600 capitalize">learn more</a>
        </div>
      </div>
    </div>
    
  </section>
  
  <section class="sevenSection">
    <div class="flex">
     <div class="carosul_fast">
      <h2 class="uppercase text-blue-600"> testimonials</h2>
      <h1 class="text-2xl font-normal capitalize"> our customers feedback</h1>
     </div>
     <div class="carosul_info hidden">
      <em>{{ carosulp }}</em>
      <div class="flex">
        <img class="rounded-full w-10 h-10" src="https://preview.colorlib.com/theme/launch/images/person_3.jpg" alt="carosul man">
        <div  class="maninfo">
          <p class="capitalize ">james anderson</p>
          <p class="capitalize font-thin text-sm">Facebook, Product Lead</p>
        </div>
      </div>
     </div>
     <div class="carosul_info">
      <em>{{ carosulp }}</em>
      <div class="flex">
        <img class="rounded-full w-10 h-10" src="https://preview.colorlib.com/theme/launch/images/person_3.jpg" alt="carosul man">
        <div  class="maninfo">
          <p class="capitalize ">james anderson</p>
          <p class="capitalize font-thin text-sm">Facebook, Product Lead</p>
        </div>
      </div>
     </div>
     <div class="carosul_info hidden">
      <em>{{ carosulp }}</em>
      <div class="flex">
        <img class="rounded-full w-10 h-10" src="https://preview.colorlib.com/theme/launch/images/person_3.jpg" alt="carosul man">
        <div  class="maninfo">
          <p class="capitalize ">james anderson</p>
          <p class="capitalize font-thin text-sm">Facebook, Product Lead</p>
        </div>
      </div>
     </div>
    </div>
  </section>


  <section class="eightSection">
    <div class="flex">
      <img src="https://preview.colorlib.com/theme/launch/images/about.svg" alt="about us" class="w-1/2">
      <div class="about_us">
        <h3 class="text-sm text-blue-600 uppercase"> about</h3>
        <h2 class="text-xl capitalize ">about us</h2>
        <p class="font-thin ">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast <br>Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia.</p>
        <ul>
          <li>{{ priceFastp }}</li>
          <li>{{ priceSecondp }}</li>
          <li>Their place and supplies</li>
        </ul>
        <div class="flex">
          <div class="m">
            <h2 class="text-xl">59M</h2>
            <p class="text-sm uppercase">members</p>
          </div>
          <div class="m">
            <h2 class="text-xl">14</h2>
            <p class="text-sm uppercase">team</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="nineSection">
    <div class="text-center">
      <h1 class="text-3xl font-normal capitalize">our news</h1>
      <p class="font-thin text-sm">Far from the countries Vokalia and Consonantia</p>
    </div>
    <div class="flex">
      <div class="shadow shadow-md shadow-blue-100 p-4 m-3 hover:mb-4 transition-all">
        <div class="flex">
          <img src="https://preview.colorlib.com/theme/launch/images/person_1.jpg" alt="newsimg" class="w-10 h-10 rounded-full">
          <div class="postUserName">
            <h2 class="text-xl capitalize font-bold ">posted by james</h2>
            <p class="font-thin capitalize font-medium">jun 14, 2020</p>
          </div>
        </div>
        <p class="text-sm font-thin">Digital Service, 4 min read</p>
        <h2 class="text-xl"> Far far away behind the word mountains far from the countries</h2>
        <img src="" alt="right icon">
      </div>

      <div class="shadow shadow-md shadow-blue-100 p-4 m-3 hover:mb-4 transition-all">
        <div class="flex">
          <img src="https://preview.colorlib.com/theme/launch/images/person_1.jpg" alt="newsimg" class="w-10 h-10 rounded-full">
          <div class="postUserName">
            <h2 class="text-xl capitalize font-bold ">posted by james</h2>
            <p class="font-thin capitalize font-medium">jun 14, 2020</p>
          </div>
        </div>
        <p class="text-sm font-thin">Digital Service, 4 min read</p>
        <h2 class="text-xl"> Far far away behind the word mountains far from the countries</h2>
        <img src="" alt="right icon">
      </div>

      <div class="shadow shadow-md shadow-blue-100 p-4 m-3 hover:mb-4 transition-all">
        <div class="flex">
          <img src="https://preview.colorlib.com/theme/launch/images/person_1.jpg" alt="newsimg" class="w-10 h-10 rounded-full">
          <div class="postUserName">
            <h2 class="text-xl capitalize font-bold ">posted by james</h2>
            <p class="font-thin capitalize font-medium">jun 14, 2020</p>
          </div>
        </div>
        <p class="text-sm font-thin">Digital Service, 4 min read</p>
        <h2 class="text-xl"> Far far away behind the word mountains far from the countries</h2>
        <img src="" alt="right icon">
      </div>

    </div>
  </section>


  <section class="tenSection">
    <div class="inputsec">
      <div class="text-center">
        <h2 class="text-4xl capitalize font-normal">get in touch</h2>
        <p class="font-thin text-sm">Far from the countries Vokalia and Consonantia</p>
      </div>
    </div>
    <div class="">
      <div class="inputbox">
        <div class="inputSec flex">
          <div class="inputfiled">
            <label class="capitalize font-thin text-sm">first name</label><br>
            <input type="text" class="input border-b-2 border-black outline-none">
          </div>
          
          <div class="inputfiled">
            <label class="capitalize font-thin text-sm">last name</label><br>
            <input type="text" class="input border-b-2 border-black outline-none">
          </div>
        </div>
        <div class="inputfiled">
            <label class="capitalize font-thin text-sm">email address</label><br>
            <input type="text" class="input border-b-2 border-black outline-none">
        </div>
        <div class="inputfiled">
            <label class="capitalize font-thin text-sm">massage</label><br>
            <textarea name="" class="input border-b-2 border-black outline-none" id="" cols="30" rows="10"></textarea>
        </div>
        <button class="bg-blue-600 uppercase rounded-full py-4 px-10 text-white">send massage</button>
      </div>
      <div class="inputsidetext">
        <h4 class="text-xl capitalize">Contact Info</h4>
        <div class="infocontac">
         <ul>
          <li>43 Raymouth Rd. Baltemoer, London 3910</li>
          <li>+1(123)-456-7890</li>
          <li>+1(123)-456-7890</li>
          <li>info@mydomain.com</li>
          <li>https://Colorlib.com/</li>
         </ul>
        </div>
      </div>
    </div>
  </section>

  <section class="elevenSection">
    <div class="flex">
      <div class="fastpart">
        <div class="">
          <h2 class="text-xl">About Launch.</h2>
          <p class="text-sm font-thin">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts.</p>
        </div>
        <div class="contact">
          <h2 class="text-xl font-bold">Connect</h2>
          <div class="flex">
            icon
          </div>
        </div>
      </div>
      <div class="secondpar">
        <h3 class="text-xl font-bold">Projects</h3>
        <ul>
          <li><a href="#">La Lega Stadium</a></li>
          <li><a href="#">France Building</a></li>
          <li><a href="#">22 New Homes</a></li>
          <li><a href="#">Manage Center</a></li>
          <li><a href="#">Sports Hall</a></li>
        </ul>
      </div>
      <div class="secondpar">
        <h3 class="text-xl font-bold">Services</h3>
        <ul>
          <li><a href="#">Architect</a></li>
          <li><a href="#">Interior Design</a></li>
          <li><a href="#">Landscape Design</a></li>
          <li><a href="#">Consultancy</a></li>
        </ul>
      </div>
      <div class="secondpar">
        <h3 class="text-xl font-bold">Contact</h3>
        <ul>
          <li><a href="#">43 Raymouth Rd. Baltemoer, London 3910</a></li>
          <li><a href="#">+1(123)-456-7890</a></li>
          <li><a href="#">+1(123)-456-7890</a></li>
          <li><a href="#">info@mydomain.com</a></li>
        </ul>
      </div>
    </div>
  </section>


</template>

<style scoped>
 .hero{
  background: url('http://nunforest.com/kinetic/upload/slide3.jpg');
  background-attachment: fixed;
 }
</style>
