<template>
    <div class="playlist h-full overflow-y-scroll">
        <div class="card">
            <div
                class="
                    md:sticky
                    top-0
                    my-3
                    pt-1
                    bg-gray-800
                    text-gray-400 text-left
                    mx-9
                "
            >
                <h2 class="text-4xl">Olá, Usuário</h2>
                <p class="text-green-400">Selecione a sua vibe de agora...</p>
            </div>
            <!-- Grid playlists -->
            <div
                class="
                    grid grid-flow-rows grid-cols-2
                    md:grid-cols-4
                    lg:grid-cols-8
                    flex-wrap
                    gap-3
                    justify-around
                    place-items-stretch
                    mx-9
                "
            >
                <div v-for="i in 7" :key="i">
                    <img
                        src="https://via.placeholder.com/128x214"
                        :alt="'playlist ' + i"
                    />
                </div>
            </div>
        </div>
    </div>
</template>
