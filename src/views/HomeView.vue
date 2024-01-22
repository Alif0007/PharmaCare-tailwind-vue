<script setup>
import ProductCard from "@/components/ProductCard.vue";
import ProductCardSmall from "@/components/ProductCardSmall.vue";
import ArticleCard from "@/components/ArticleCard.vue";
</script>

<template>
  <main>
    <div>
      <div class="flex justify-between max-w-5xl mx-auto mb-6">
        <div class="flex gap-4 ml-6">
          <p>Info :+880 178729937</p>
          <p>About</p>
          <p>Delivery information</p>
        </div>
        <div class="flex gap-4 mr-6">
          <p>FAQ</p>
          <p>English</p>
        </div>
      </div>
      <!-- Header ------------- -->
      <div class="flex justify-center max-w-6xl mx-auto gap-8">
        <h1 class="text-3xl font-bold text-green-500">PharmaCare</h1>
        <div class="flex">
          <input
            class="pl-4 w-80 h-10 border-gray-500 border"
            type="text"
            placeholder="Search"
          />
          <ion-icon
            class="h-10 w-12 text-3xl bg-green-500"
            name="search"
          ></ion-icon>
        </div>
        <div class="flex items-center gap-1">
          <ion-icon class="text-3xl text-green-500" name="person"></ion-icon>
          <div>
            <p class="font-semibold">Account</p>
            <p class="text-xs">Login / Register</p>
          </div>
        </div>
        <div class="flex items-center gap-1">
          <ion-icon class="text-3xl text-green-500" name="heart"></ion-icon>
          <div>
            <p class="font-semibold">Wishlist</p>
            <p class="text-xs">Edit Your Wishlist</p>
          </div>
        </div>
        <div class="flex items-center gap-1">
          <ion-icon class="text-3xl text-green-500" name="cart"></ion-icon>
          <div>
            <p class="font-semibold">Cart</p>
            <p class="text-xs">$0.00</p>
          </div>
        </div>
      </div>

      <!-- Navbar-------- -->

      <div>
        <div
          class="bg-green-500 flex items-center justify-between text-white mt-6"
        >
          <ul class="flex ml-60">
            <li class="p-4"><a href="">Home</a></li>
            <li class="p-4"><a href="">Pages</a></li>
            <li class="p-4"><a href="">Shop</a></li>
            <li class="p-4"><a href="">Blog</a></li>
            <li class="p-4"><a href="">Landing</a></li>
          </ul>
          <div class="mr-40"><p>ASK YOUR PHARMACIST</p></div>
        </div>
      </div>

      <!---------- Banner -------->

      <div class="relative" style="height: 100vh">
        <div class="absolute">
          <img src="../assets/Rectangle 5.png" alt="" />
        </div>
        <div class="w-2/5 absolute top-36 left-24">
          <h1 class="text-6xl text-white font-bold mb-4">
            Daily Routine for Good Health
          </h1>
          <p class="text-white text-xl">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Modi
            magnam doloremque est ex debitis similique fuga, dicta illo cum
            dolorem.
          </p>
          <button class="py-2 px-4 text-white mt-8 font-semibold bg-green-400">
            Buy Now
          </button>
        </div>
      </div>
      <!------------- What do you need today?--------- -->

      <div>
        <h1 class="text-3xl font-semibold text-center mb-8">
          What do you need today?
        </h1>
        <div class="grid md:grid-cols-2 grid-cols-1 max-w-5xl mx-auto gap-4">
          <div class="grid grid-cols-1">
            <ProductCard />
          </div>
          <div class="grid grid-cols-2 gap-4">
            <ProductCard />
            <ProductCard />
            <ProductCard />
            <ProductCard />
          </div>
        </div>
      </div>

      <div>
        <div class="grid grid-cols-3 max-w-5xl mx-auto mt-16 gap-6">
          <img src="..\assets\Rectangle 10.png" alt="" />
          <img src="..\assets\Rectangle 11.png" alt="" />
          <img src="..\assets\Rectangle 10.png" alt="" />
        </div>
      </div>

      <!------------ Vitamins & Minerals ---------->

      <div class="max-w-5xl mx-auto">
        <h1 class="text-3xl font-semibold my-10">Vitamins & Minerals</h1>
        <div class="grid md:grid-cols-4 grid-cols-2 gap-4">
          <ProductCard />
          <ProductCard />
          <ProductCard />
          <ProductCard />
        </div>
      </div>

      <!-------- Cold & Fever ------->

      <div class="max-w-5xl mx-auto">
        <h1 class="text-3xl font-semibold my-10">Cold & Fever</h1>
        <div class="grid md:grid-cols-5 gap-4 gap-y-11 grid-cols-3">
          <ProductCardSmall />
          <ProductCardSmall />
          <ProductCardSmall />
          <ProductCardSmall />
          <ProductCardSmall />
          <ProductCardSmall />
          <ProductCardSmall />
          <ProductCardSmall />
          <ProductCardSmall />
          <ProductCardSmall />
        </div>
      </div>
      <div class="flex mt-12">
        <div class="w-3/5 bg-green-600 text-white p-20">
          <h1 class="text-5xl font-semibold mb-6">
            What supplements should I take daily?
          </h1>
          <p class="text-lg mb-8">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sederet
            diam nonumy eirmod tempor invidunt ut labore ipsum dolor sit amet,
            consectetuer adipiscing
          </p>
          <div class="flex gap-1 items-center">
            <img src="../assets/Ellipse 5.png" alt="" />
            <div>
              <p class="font-bold">Doctor Nancy</p>
              <p class="text-xs">Dermatologist</p>
            </div>
          </div>
        </div>
        <div>
          <img src="../assets/Rectangle 19.png" alt="" />
        </div>
      </div>

      <!------------------ Article & Tips------------- -->

      <div class="bg-gray-100">
        <h1 class="text-3xl font-semibold mt-16 text-center mb-6">
          Article & Tips
        </h1>

        <div
          class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-5xl mx-auto pb-8"
        >
          <ArticleCard />
          <ArticleCard />
          <ArticleCard />
        </div>
      </div>

      <!------------- Footer ------->

      <div class="max-w-5xl mx-auto grid grid-cols-4 gap-28 mt-12">
        <div>
          <h1 class="text-3xl font-bold text-green-500 mb-6">PharmaCare</h1>
          <p class="text-xs mb-2">
            Lorem Ipsum has been the industry's standard dummy text ever since
            1500s, when an unknown printer took a galley of type and scrambled
            it to make a type.
          </p>
          <p class="text-lg mb-2">Contact</p>
          <p>+ (713)534-2319</p>
          <p>+ (733)364-5123</p>
          <p>+ (265)445-1158</p>
        </div>
        <div>
          <h1 class="text-2xl font-bold mb-6">Working Hours</h1>
          <h2 class="text-lg font-bold">Pharmacy City Center</h2>
          <p class="text-xs mb-4">
            Monday to Sunday 7 am to 9 pm 45 Hudson Street Villa Rica, GA 30180
          </p>
          <h2 class="text-lg font-bold">Pharmacy Old Town</h2>
          <p class="text-xs">
            Monday to Saturday 8 am to 5 pm Sunday – Closed 95 East Baker Street
            Union City, NJ 07087
          </p>
        </div>
        <div>
          <h1 class="text-2xl font-bold mb-6">Service</h1>
          <ul>
            <li>Terms & Conditions</li>
            <li>Payment methods</li>
            <li>Privacy Policy</li>
            <li>Cancel the contract</li>
            <li>Product complaint</li>
            <li>FAQ</li>
          </ul>
        </div>
        <div>
          <h1 class="text-2xl font-bold">Instagram</h1>
        </div>
      </div>
      <footer class="bg-green-400 text-white mt-12 text-center">
        <p>@ 2023 iCircles, All Rights Reserved</p>
      </footer>
    </div>
  </main>
</template>

<style>
* {
  margin: 0%;
  padding: 0%;
}
</style>
