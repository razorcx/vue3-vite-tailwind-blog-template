<script setup>
</script>

<template>
    <section class=" container mx-auto px-4 py-10 lg:py-16">
        <div class=" flex items-center justify-between">
            <h2 class=" text-gray-800 font-bold text-3xl">Podcasts</h2>

            <button
                class="flex items-center px-4 py-2.5 font-medium tracking-wide text-sky-500 capitalize transition-colors duration-300 transform border border-sky-500 rounded-lg hover:bg-sky-50 focus:outline-none focus:ring focus:ring-sky-300 focus:ring-opacity-80">
                <span class="mx-1">Exploer All</span>

                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-6 mx-1 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
                </svg>
            </button>
        </div>

        <div class="grid grid-cols-1 gap-8 md:grid-cols-2 mt-12 xl:grid-cols-3">
            <div>
                <img class="object-cover object-center w-full h-64 rounded-lg lg:h-80"
                    src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTbDroD8JBly4YN-kttERe-REhf1Ago4jgen2nZFLR0wjm2IKU"
                    alt="">

                <div class="mt-8">
                    <span class="text-sky-500 uppercase tracking-wider">Podcast</span>

                    <h1 class="mt-4 text-xl font-semibold text-gray-800 dark:text-white truncate">
                        057: DevTools Mini Series - Interaction
                    </h1>

                    <p class="mt-2 text-gray-500 dark:text-gray-400">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam est asperiores vel, ab animi
                        recusandae nulla veritatis id tempore sapiente
                    </p>

                    <div class="flex items-center justify-between mt-4">
                        <div>
                            <a href="#"
                                class="text-lg font-medium text-gray-700 dark:text-gray-300 hover:underline hover:text-gray-500">
                                John snow
                            </a>

                            <p class="text-sm text-gray-500 dark:text-gray-400">February 1, 2022</p>
                        </div>

                        <a href="#" class="inline-block text-sky-500 underline hover:text-sky-400">Open Episode</a>
                    </div>

                </div>
            </div>

            <div>
                <img class="object-cover object-center w-full h-64 rounded-lg lg:h-80"
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRb1UizkegO75CK7joXI5YU_PyD-PrAKQj2reAOV99r4O5Ic3Y"
                    alt="">

                <div class="mt-8">
                    <span class="text-sky-500 uppercase tracking-wider">Podcast</span>

                    <h1 class="mt-4 text-xl font-semibold text-gray-800 dark:text-white truncate">
                        Steal From Other Hobbies
                    </h1>

                    <p class="mt-2 text-gray-500 dark:text-gray-400">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam est asperiores vel, ab animi
                        recusandae nulla veritatis id tempore sapiente
                    </p>

                    <div class="flex items-center justify-between mt-4">
                        <div>
                            <a href="#"
                                class="text-lg font-medium text-gray-700 dark:text-gray-300 hover:underline hover:text-gray-500">
                                Jeffrey Way
                            </a>

                            <p class="text-sm text-gray-500 dark:text-gray-400">February 6, 2022</p>
                        </div>

                        <a href="#" class="inline-block text-sky-500 underline hover:text-sky-400">Open Episode</a>
                    </div>

                </div>
            </div>

            <div>
                <img class="object-cover object-center w-full h-64 rounded-lg lg:h-80"
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQe9M4BrVwjAO9HM8h1tNhWJ0iOah_ERztSZKs8D2DrxSexPFs"
                    alt="">

                <div class="mt-8">
                    <span class="text-sky-500 uppercase tracking-wider">Podcast</span>

                    <h1 class="mt-4 text-xl font-semibold text-gray-800 dark:text-white truncate">
                        152: Ben Orenstein - How to Stand Out When Applying for a Job at a Small Company
                    </h1>

                    <p class="mt-2 text-gray-500 dark:text-gray-400">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam est asperiores vel, ab animi
                        recusandae nulla veritatis id tempore sapiente
                    </p>

                    <div class="flex items-center justify-between mt-4">
                        <div>
                            <a href="#"
                                class="text-lg font-medium text-gray-700 dark:text-gray-300 hover:underline hover:text-gray-500">
                                Adam Wathan
                            </a>

                        <p class="text-sm text-gray-500 dark:text-gray-400">February 19, 2022</p>
                    </div>

                    <a href="#" class="inline-block text-sky-500 underline hover:text-sky-400">Open Episode</a>
                </div>
            </div>
        </div>
    </div>
</section></template>