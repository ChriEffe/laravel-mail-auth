<template>
    <div>
        <Header/>
        <router-view></router-view>
    </div>
</template>

<script>
import Header from '../components/Header.vue';
import Main from '../components/Main.vue';

export default {
    name: 'app',
    components: {
        Header,
        Main
    }
}
</script>

<style lang="scss" scoped>

</style>