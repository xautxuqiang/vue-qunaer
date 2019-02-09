<template>
    <div class="home">
        <home-header></home-header>
    </div>
</template>

<script>
import HomeHeader from './components/header';
export default {
    name: 'Home',
    components: {
        HomeHeader
    }
}
</script>

<style lang="stylus" scoped>
    .home
        margin: 10px
        width: 750px
</style>