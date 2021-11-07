<template>
    <nav>
        <router-link :to="{ name: 'home' }">Accueil</router-link> |
        <router-link :to="{ name: 'about' }">A propos</router-link>

    </nav>
</template>
<script>
export default {
    name: "navbar",

};

</script>
<style lang="scss">

</style>
