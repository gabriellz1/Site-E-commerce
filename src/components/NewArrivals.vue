<template>
    <section class="py-5">
      <div class="container text-center">
        <h2 class="fw-bold mb-4">NEW ARRIVALS</h2>
        <div class="row g-4 justify-content-center">
          <div class="col-6 col-md-4 col-lg-3" v-for="(product, index) in products" :key="index">
            <ProductCard :image="product.image" :name="product.name" :price="product.price" />
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  import ProductCard from './ProductCard.vue'
  
  export default {
    name: 'NewArrivals',
    components: { ProductCard },
    data() {
      return {
        products: [
          {
            image: 'https://i.imgur.com/8Km9tLL.png',
            name: 'T-Shirt With Tape Details',
            price: '$120'
          },
          {
            image: 'https://i.imgur.com/VHbXrDj.png',
            name: 'Skinny Fit Jeans',
            price: '$150'
          },
          {
            image: 'https://i.imgur.com/XKFkBbn.png',
            name: 'Black Leather Jacket',
            price: '$220'
          },
          {
            image: 'https://i.imgur.com/9M5OHPp.png',
            name: 'Oversized Hoodie',
            price: '$180'
          }
        ]
      }
    }
  }
  </script>
  