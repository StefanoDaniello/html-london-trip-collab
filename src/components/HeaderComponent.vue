<template>
    <header>
        <nav>
            <div class="logo">
                <img :src="img" alt="logo">
            </div>
            <ul>
                <li v-for="(item, index) in navList" :key="index"><a href="#" class="ms-3">{{ item }}</a></li>
            </ul>
        </nav>
    </header>
</template>

<script>
    export default {
        name: 'HeaderComponent',
        data() {
            return {
                navList: ['Home', 'Chi siamo', 'Dove siamo', 'Contatti'],
                img: '../public/images/vintage-bar-bistro.jpg'
            }
        }
    }
</script>

<style lang="scss" scoped>
@use './src/assets/styles/partials/variables' as *;
.logo{
    width: 200px;
    img{
        width: 100%;
    }
}
nav, ul{
    @include wp-flex;
}
ul{
    list-style: none;
    a{
        text-decoration: none;
    }
}
</style>