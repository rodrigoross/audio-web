<template>
    <div class="home h-full">
        <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
        <div class="w-auto py-2 md:float-right mx-3">
            <input
                class="rounded-lg px-1"
                type="search"
                name="Buscar"
                id="busca"
                placeholder="Procure sua vibe"
            />
        </div>
        <div class="text-gray-400">
            <table class="table-auto text-left w-full place-items-end">
                <thead>
                    <tr class="text-gray-300">
                        <th></th>
                        <th>Música</th>
                        <th>Artista</th>
                        <th class="hidden md:block">Album</th>
                        <th>Playtime</th>
                    </tr>
                </thead>
                <tbody class="divide-y">
                    <tr>
                        <td>+</td>
                        <td>Intro to CSS</td>
                        <td>Adam</td>
                        <td class="hidden md:block">Adam Inc</td>
                        <td>858</td>
                    </tr>
                    <tr>
                        <td>+</td>
                        <td>A Long and Winding Tour of</td>
                        <td>Adam</td>
                        <td class="hidden md:block">Adam La</td>
                        <td>112</td>
                    </tr>
                    <tr>
                        <td>+</td>
                        <td>Intro to JavaScript</td>
                        <td>Chris</td>
                        <td class="hidden md:block">XoRG</td>
                        <td>1,280</td>
                    </tr>
                    <tr>
                        <td>+</td>
                        <td>Intro to JavaScript</td>
                        <td>Chris</td>
                        <td class="hidden md:block">eNABLED</td>
                        <td>1,280</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</template>

<script>
// @ is an alias to /src

export default {
    name: 'Home'
};
</script>
