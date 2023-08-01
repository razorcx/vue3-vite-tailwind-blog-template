<script setup>
</script>

<template>
    <section class=" container mx-auto px-4 py-10 lg:py-16">
        <div class=" flex items-center justify-between">
            <h2 class=" text-gray-800 font-bold text-3xl">Most Popular</h2>

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
                    src="https://images.unsplash.com/photo-1624996379697-f01d168b1a52?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
                    alt="">

                <div class="mt-8">
                    <span class="text-sky-500 uppercase tracking-wider">Article</span>

                    <h1 class="mt-4 text-xl font-semibold text-gray-800 dark:text-white truncate">
                        What do you want to know about UI
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

                        <a href="#" class="inline-block text-sky-500 underline hover:text-sky-400">Read more</a>
                    </div>

                </div>
            </div>

            <div>
                <img class="object-cover object-center w-full h-64 rounded-lg lg:h-80"
                    src="https://images.unsplash.com/photo-1590283603385-17ffb3a7f29f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
                    alt="">

                <div class="mt-8">
                    <span class="text-sky-500 uppercase tracking-wider">Article</span>

                    <h1 class="mt-4 text-xl font-semibold text-gray-800 dark:text-white truncate">
                        All the features you want to know</h1>

                    <p class="mt-2 text-gray-500 dark:text-gray-400">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam est asperiores vel, ab animi
                        recusandae nulla veritatis id tempore sapiente
                    </p>

                    <div class="flex items-center justify-between mt-4">
                        <div>
                            <a href="#"
                                class="text-lg font-medium text-gray-700 dark:text-gray-300 hover:underline hover:text-gray-500">
                                Arthur Melo
                            </a>

                            <p class="text-sm text-gray-500 dark:text-gray-400">February 6, 2022</p>
                        </div>

                        <a href="#" class="inline-block text-sky-500 underline hover:text-sky-400">Read more</a>
                    </div>

                </div>
            </div>

            <div>
                <img class="object-cover object-center w-full h-64 rounded-lg lg:h-80"
                    src="https://images.unsplash.com/photo-1597534458220-9fb4969f2df5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1374&q=80"
                    alt="">

                <div class="mt-8">
                    <span class="text-sky-500 uppercase tracking-wider">Article</span>

                    <h1 class="mt-4 text-xl font-semibold text-gray-800 dark:text-white truncate">
                        Which services you get from Meraki UI
                    </h1>

                    <p class="mt-2 text-gray-500 dark:text-gray-400">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam est asperiores vel, ab animi
                        recusandae nulla veritatis id tempore sapiente
                    </p>

                    <div class="flex items-center justify-between mt-4">
                        <div>
                            <a href="#"
                                class="text-lg font-medium text-gray-700 dark:text-gray-300 hover:underline hover:text-gray-500">
                                Tom Hank
                            </a>

                        <p class="text-sm text-gray-500 dark:text-gray-400">February 19, 2022</p>
                    </div>

                    <a href="#" class="inline-block text-sky-500 underline hover:text-sky-400">Read more</a>
                </div>
            </div>
        </div>
    </div>
</section></template>