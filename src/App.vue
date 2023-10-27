<script setup>
import { RouterView } from 'vue-router'
import TopMenu from './components/TopMenu/TopMenu.vue'
import NavigationBar from './components/NavigationBar/NavigationBar.vue'

</script>

<template>
  <div class="app-wrapper">
    <header class="header">
    <div class="wrapper">
      <div class="header-line">
        <div class="header-line-logo">
          <p>ЛОГОТИП</p>
        </div>
        <div class="header-line-search">
          <input type="text" placeholder="Поиск">
        </div>
        <TopMenu />
      </div>

    </div>
  </header>
 
  </div>
  <div class="content">
    <NavigationBar />
    <RouterView />
  </div>





</template>

<style lang="scss">
@import './App.scss';
</style>
