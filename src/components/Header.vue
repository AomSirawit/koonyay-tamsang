<script setup>
import { RouterLink } from 'vue-router';


</script>

<template>
    <div class="navbar bg-base-100 shadow-lg sticky top-0">
  <div class="flex-1">
    <img src="../assets/logoAndCover/logo.png" alt="" class="w-12">
    <p class="text-sm">สนใจสั่งอาหาร​ โทร 096-xxxxx</p>
  </div>
  <div class="flex-none">
    <ul class="menu menu-horizontal px-1">
      <li><RouterLink to="/">หน้าหลัก</RouterLink></li>
      <li><RouterLink to="/menu">เมนูอาหาร</RouterLink></li>
      <li><RouterLink to="/contact">ติดต่อ</RouterLink></li>
    </ul>
  </div>
</div>

</template>