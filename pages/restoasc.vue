<template>
    <div>
        <section class="relative w-full">
        <div class="absolute top-0 inset-x-0 h-64 flex items-start">
            <div
                class="h-24 w-2/3 bg-gradient-to-br from-primary opacity-20 blur-2xl dark:from-[#570cac] dark:invisible dark:opacity-40">
            </div>
            <div
                class="h-20 w-3/5 bg-gradient-to-r from-[#8cd66a] opacity-40 blur-2xl dark:from-[#670ccf] dark:opacity-40">
            </div>
        </div>
        <AtomsContainer class-name="relative">
            <div aria-hidden="true" class="absolute inset-y-0 w-44 left-0 hidden dark:flex">
                <div
                    class="h-full md:h-1/2 lg:h-full w-full bg-gradient-to-tr opacity-40 dark:blur-2xl dark:from-[#570cac] dark:opacity-20">
                </div>
            </div>
            <div
                class="grid lg:grid-cols-2 gap-10 xl:gap-14 relative pt-24 lg:max-w-none max-w-2xl md:max-w-3xl mx-auto">
                <div class="lg:py-6">
                    <div class="text-center lg:text-left">
                        <span class="px-2 py-1 rounded-md bg-indigo-950 dark:bg-body text-[#f4ac1b] ">Restaurant
                            </span>
                        <h1 class="text-gray-800 pt-4 dark:text-white font-bold text-4xl md:text-5xl lg:text-6xl">
                            Le Restaurant  <br> <span
                                class="text-transparent bg-clip-text bg-gradient-to-br from-[#cd3a01] to-[#f4ac1b]">Wakadjêhoun</span>
                        </h1>
                    </div>                    
                </div>                
            </div>
        </AtomsContainer>
    </section>
        <SectionsHomePopularPodcasts/>
        <SectionsCallToAction/>
    </div>
</template>