<template>
    <div class="player-wrapper">
        <div class="">
            <div class="border-t-4 border-green-500"></div>
            <div class="flex gap-x-1">
                <div class="m-1 md:m-0">
                    <img
                        class="py-auto"
                        src="https://via.placeholder.com/64"
                        alt="capa album"
                    />
                </div>
                <div
                    class="
                        flex flex-col
                        place-content-between
                        md:place-content-stretch
                        py-1
                        w-full
                    "
                >
                    <div
                        class="
                            text-left text-gray-400 text-sm
                            md:text-md
                            lg:text-lg
                            xl:text-xl
                        "
                    >
                        <p>
                            Nome musica
                            <span class="text-gray-700">nome album</span>
                        </p>
                    </div>
                    <!-- Player Controllers -->
                    <div
                        class="
                            flex
                            gap-3
                            items-between
                            justify-start
                            md:justify-center
                        "
                    >
                        <img
                            src="https://via.placeholder.com/24x24"
                            alt="player volta"
                        />
                        <img
                            src="https://via.placeholder.com/24x24"
                            alt="player volta 10s"
                        />
                        <img
                            src="https://via.placeholder.com/24x24"
                            alt="player pausa/play"
                        />
                        <img
                            src="https://via.placeholder.com/24x24"
                            alt="player avança 10s"
                        />
                        <img
                            src="https://via.placeholder.com/24x24"
                            alt="player volta"
                        />
                    </div>
                </div>
                <!-- <div class="center">
                    <img src="https://via.placeholder.com/24x24" alt="expandir playlist">
                </div> -->
            </div>
        </div>
    </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.player-wrapper {
    @apply fixed bottom-0 h-16 w-full;
    @apply bg-gray-900;
}
</style>
