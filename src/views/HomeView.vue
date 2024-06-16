<script setup></script>

<template>
  <div>
    <img class="w-fit" src="../assets/logoAndCover/cover.png" alt="" />
  </div>
  <div>
    <div class="m-10">
      <h1 class="font-semibold text-3xl">เมนูขายดี</h1>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 m-10">
      <div class=" bg-base-100 shadow-xl rounded-lg w-full max-w-xs mx-auto">
        <figure>
          <img
            class="object-fit w-full h-52 rounded-t-lg"
            src="../assets/foodImg/kaijeaw.jpeg"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title m-auto font-normal text-lg">ข้าวไข่เจียว</h2>
          <div class="card-actions justify-center">
            <button class="btn btn-neutral w-44 text-white">30฿</button>
          </div>
        </div>
      </div>

      <div class="bg-base-100 shadow-xl rounded-lg w-full max-w-xs mx-auto">
        <figure>
          <img
            class="object-fit w-full h-52 rounded-t-lg"
            src="../assets/foodImg/thai-basil-pork.jpg"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title m-auto font-normal text-lg">
            ข้าวกระเพราหมูสับ
          </h2>
          <div class="card-actions justify-center">
            <button class="btn btn-neutral w-44 text-white">35฿</button>
          </div>
        </div>
      </div>

      <div class="bg-base-100 shadow-xl rounded-lg w-full max-w-xs mx-auto">
        <figure>
          <img
            class="object-fit w-full h-52 rounded-t-lg"
            src="../assets/foodImg/nooddle.jpg"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title m-auto font-normal text-lg">ก๋วยเตี๋ยวเรือ</h2>
          <div class="card-actions justify-center">
            <button class="btn btn-neutral w-44 text-white">35฿</button>
          </div>
        </div>
      </div>

      <div class="bg-base-100 shadow-xl rounded-lg w-full max-w-xs mx-auto">
        <figure>
          <img
            class="object-fit w-full h-52 rounded-t-lg"
            src="../assets/foodImg/mootod-krateam.jpg"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title m-auto font-normal text-lg">
            ข้าวหมูทอดกระเทียม
          </h2>
          <div class="card-actions justify-center">
            <button class="btn btn-neutral w-44 text-white">30฿</button>
          </div>
        </div>
      </div>

      <div class="bg-base-100 shadow-xl rounded-lg w-full max-w-xs mx-auto">
        <figure>
          <img
            class="object-fit w-full h-52 rounded-t-lg"
            src="../assets/foodImg/pad-thai.jpg"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title m-auto font-normal text-lg">ผัดไทย</h2>
          <div class="card-actions justify-center">
            <button class="btn btn-neutral w-44 text-white">40฿</button>
          </div>
        </div>
      </div>

      <div class="bg-base-100 shadow-xl rounded-lg w-full max-w-xs mx-auto">
        <figure>
          <img
            class="object-fit w-full h-52 rounded-t-lg"
            src="../assets/foodImg/sukiyaki.jpg"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title m-auto font-normal text-lg">สุกี้น้ำ</h2>
          <div class="card-actions justify-center">
            <button class="btn btn-neutral w-44 text-white">40฿</button>
          </div>
        </div>
      </div>
    </div>
    <div class="flex justify-center mt-10 mb-10">
      <router-link to="/menu">
        <button class="btn btn-neutral w-52 text-white">ดูเมนูทั้งหมด</button>
      </router-link>
    </div>
  </div>
</template>
