<template>
  <div>
    <Banner />
    <CategoryProducts :tabs="womentabs" :title="womentitle" :products="womenProducts" />
    <CategoryProducts :tabs="womentabs" :title="mentitle" :products="womenProducts" />
    <Feauterd />
    <Subscribe />
    <Blogs />
    <Footer />
  </div>
</template>


<script setup>
import { ref } from 'vue'
import Banner from '@/components/Banner.vue';
import CategoryProducts from '@/components/CategoryProducts.vue';
import Feauterd from '@/components/Feauterd.vue';
import Subscribe from '@/components/Subscribe.vue';
import Blogs from '@/components/Blogs.vue';
import Footer from '@/components/Footer.vue';
const womentabs = ref([
  "NEW ARRIVALS",
  "SPECIALS",
  "BESTSELLERS",
  "MOST VIEWED",
  "FEATURED PRODUCTS",
]);

const womenProducts = ref([
  {
    img: "../assets/images/p1.jpg",
    sale: false,
    name: `Women's tracksuit Q109`,
    price: "$ 38.00",
    rating: "../assets/images/rating.png",
  },
  {
    img: "../assets/images/p2.png",
    sale: true,
    name: `Women's tracksuit Q109`,
    price: "$ 38.00",
    rating: "../assets/images/rating.png",
  },
  {
    img: "../assets/images/p3.png",
    sale: false,
    name: `Women's tracksuit Q109`,
    price: "$ 38.00",
    rating: "../assets/images/rating.png",
  },
  {
    img: "../assets/images/p2.png",
    sale: false,
    name: `Women's tracksuit Q109`,
    price: "$ 38.00",
    rating: "../assets/images/rating.png",
  },
  {
    img: "../assets/images/p3.png",
    sale: false,
    name: `Women's tracksuit Q109`,
    price: "$ 38.00",
    rating: "../assets/images/rating.png",
  },
  {
    img: "../assets/images/p1.jpg",
    sale: false,
    name: `Women's tracksuit Q109`,
    price: "$ 38.00",
    rating: "../assets/images/rating.png",
  },
  {
    img: "../assets/images/p3.png",
    sale: false,
    name: `Women's tracksuit Q109`,
    price: "$ 38.00",
    rating: "../assets/images/rating.png",
  },
  {
    img: "../assets/images/p2.png",
    sale: false,
    name: `Women's tracksuit Q109`,
    price: "$ 38.00",
    rating: "../assets/images/rating.png",
  },
]);
const womentitle = ref("Womens");
const mentitle = ref("Men");
</script>
