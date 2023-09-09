<template>
    <div class="w-full relative rounded-2xl overflow-hidden">
        <nuxt-img :src="coverImage" alt="Cover image" width="2280" class="w-full aspect-square object-cover rounded-2xl" />
        <span class="absolute top-2 right-2 px-2 rounded-full text-sm text-white bg-primary">
            {{ date }}
        </span>
        <div
            class="absolute py-2 px-3 md:py-3 md:px-4 bottom-0 h-28 flex flex-col  inset-x-0 bg-gradient-to-t from-gray-800 bg-opacity-50 backdrop-filter backdrop-blur-sm">
            <h4 class="text-white font-semibold text-sm sm:text-base ">
                {{ title }}
            </h4> 
            <h2 class="text-white font-semibold text-sm sm:text-base ">
               avec {{ artiste }}
            </h2>
            <div class="pt-2">
                <NuxtLink :to="href"
                    class="flex items-center text-white rounded-full p-0.5 pr-2 gap-2 text-sm border border-gray-100/20 w-max">
                    <span class="p-1 rounded-full bg-primary">
                        
                    </span>
                    En savoir plus
                </NuxtLink>
            </div>
        </div>
    </div>
</template>

<script lang="ts" setup>
const { title, href, date, lieu,  artiste,  prix, coverImage } = defineProps<{
    title: string,
    href: string,
    date: string,
    artiste: string,
    lieu: string,
    prix: string,
    coverImage: string
}>()
</script>