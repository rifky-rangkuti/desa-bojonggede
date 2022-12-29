<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold mt-4">Visi</p>
      <p>Membangun desa digital</p>
      <p class="text-lg font-semibold mt-4">Misi</p>
      <ul>
        <li>Misi 1 desa masing-masing</li>
        <li>Misi 2 desa masing-masing</li>
        <li>Misi 3 desa masing-masing</li>
        <li>Misi 4 desa masing-masing</li>
      </ul>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desa-bojonggede.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
