<template>
    <div class="header">
        <router-link class="header__btn" :to="{ name: 'home' }">Сравнение с группой</router-link>
        <router-link class="header__btn" :to="{ name: 'ManyToMany' }">Сравнение между собой</router-link>
    </div>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
.header {
    display: flex;
    background-color: #F2F2F2;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.header__btn {
    padding: 25px 42px;
    font-weight: 400;
}

.header__btn:hover {
    font-weight: 500;
}
</style>