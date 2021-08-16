<template>
    <div class="player-wrapper flex items-center gap-x-1">
        <div class="flex-initial m-1">
            <img src="https://via.placeholder.com/46" alt="capa album">
        </div>
        <div class="text-gray-400 text-sm flex-col">
            <div class="text-left">
                <p>Nome musica / nomeAlbum</p>
            </div>
            <div class="max-w-full pr-2">
                <img src="https://via.placeholder.com/320x5" alt="player status">
            </div>
        </div>
    </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.player-wrapper {
    @apply fixed bottom-0 max-h-20 w-full;
    @apply bg-gray-900;
}
</style>
