<template>
    <nav class="navbar navbar-expand-md navbar-light bg-white shadow-sm">
        <div class="container">          
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">

                <li class="nav-item">
                    <router-link class="nav-link" :to="{ name: 'home' }">Home</router-link>
                </li>

                <li class="nav-item" >
                    <router-link class="nav-link" :to="{ name: 'contacts' }">Contatti</router-link>
                </li>

                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            menuItems: [
                    {
                        label: 'Home',
                        routeName: 'home',
                    },
                    {
                        label: 'Contatti',
                        routeName: 'contacts',
                    }
                ],
        }
    }
}
</script>

<style lang="scss" scoped>

</style>