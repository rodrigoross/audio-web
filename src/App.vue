<template>
    <main class="bg-gray-800 flex divide-x divide-gray-700">
        <div class="hidden md:block">
            <div id="nav" class="flex flex-col text-left">
                <router-link to="/">Home</router-link>
                <router-link to="/about">Playlists</router-link>
            </div>
        </div>
        <router-view class="w-full"/>
    </main>
    <ThePlayer />
</template>
<script>
import ThePlayer from '@/components/layouts/ThePlayer.vue';

export default {
    components: {
        ThePlayer
    }
};
</script>

<style lang="scss">
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    height: 100%;
}

#nav {
    padding: 30px;

    a {
        font-weight: bold;
        color: #2c3e50;

        &.router-link-exact-active {
            color: #42b983;
        }
    }
}

html,
body,
main {
    height: 100%;
}
</style>
