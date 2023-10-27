<script setup>
    import { RouterLink } from 'vue-router'
</script>

<template>
    <div class="bar-wrapper">
        <div class="icon-user">
            <p>Image User</p>
            <div class="icon-user-gears">&#9965;</div>
        </div>
        <nav class="navigation-links">
            <RouterLink to="/">Приход</RouterLink>
            <RouterLink to="/products">Группы</RouterLink>
            <p>Продукты</p>
            <p>Пользователь</p>
            <p>Настройка</p> 
        </nav>
    </div>
</template>

<style lang="scss">
@import './NavigationBar.scss';
</style>