<template>
    <section class="py-20">
        <AtomsContainer>
            <div
                class="w-full relative py-8 md:py-10 px-6 md:px-8 rounded-2xl bg-gradient-to-tr from-gray-100 to-gray-200 dark:from-gray-900 dark:to-body-color">
                <div class="absolute right-0 top-0 h-full w-full flex justify-end">
                    <span class="flex opacity-20">
                        <span class="w-16 h-32 rounded-l-full flex bg-primary blur-2xl"></span>
                        <span class="w-16 h-32 rounded-r-full flex bg-[#f88fc2] blur-2xl mt-14"></span>
                    </span>
                </div>

                <div class="absolute left-0 bottom-0 h-full w-full flex items-end">
                    <span class="flex opacity-20">
                        <span class="w-16 h-32 rounded-l-full flex bg-primary blur-2xl"></span>
                        <span class="w-16 h-32 rounded-r-full flex bg-[#f88fc2] blur-2xl mt-14"></span>
                    </span>
                </div>
                <div class="mx-auto text-center max-w-xl md:max-w-2xl relative">
                    <h2 class="text-gray-800 pt-4 dark:text-white font-bold text-4xl md:text-5xl lg:text-6x">
                        Réservez vos <span
                            class="text-transparent bg-clip-text bg-gradient-to-br from-primary to-[#8cd66a]">séances</span>
                             de répétitions
                    </h2>
                    <p class="text-gray-600 dark:text-gray-300 pt-8 mx-auto max-w-xl">
                        
                    </p>
                    <div class="mx-auto max-w-md sm:max-w-xl pt-10">
                        <form action="" class="block items-left relative gap-x-8">
                            <div class="form-control "  style="margin: 5px;">
                                <input type="text" placeholder=" Téléphone ex. (+229XXXXXXXX)" class=" md:max-w-2xl outline-none border-2 border-transparent focus:border-primary bg-body text-gray-600 dark:text-gray-200 rounded-3xl px-6 py-3 w-full">
                            </div>
                            <div class="form-control sm:max-w-xl" style="margin: 5px;">
                                <input type="email" placeholder="Email ex. (johndoe@gmail.com)" class=" md:max-w-2xl outline-none border-2 border-transparent focus:border-primary bg-body text-gray-600 dark:text-gray-200 rounded-3xl px-6 py-3 w-full">
                            </div>
                            <div class="form-control sm:max-w-xl" style="margin: 5px;">
                                <label for="date" class="text-gray-800 dark:text-white font-bold pt-8 mx-auto max-w-xl">Date et heure de répétition</label>
                                <input type="datetime-local" placeholder="Date et heure de répétition" class=" md:max-w-2xl outline-none border-2 border-transparent focus:border-primary bg-body text-gray-600 dark:text-gray-200 rounded-3xl px-6 py-3 w-full">
                            </div>
                            <div class="form-control sm:max-w-xl" style="margin: 5px;">
                                <input type="number" placeholder="Nombre d'heure à réserver" min="1" class=" md:max-w-2xl outline-none border-2 border-transparent focus:border-primary bg-body text-gray-600 dark:text-gray-200 rounded-3xl px-6 py-3 w-full">
                            </div>
                            <div class="form-control sm:max-w-xl" style="margin: 5px;">
                                <select aria-placeholder="Choissez la salle"  class=" md:max-w-2xl outline-none border-2 border-transparent focus:border-primary bg-body text-gray-600 dark:text-gray-200 rounded-3xl px-6 py-3 w-full">
                                    <option value="0">--Choissez la salle--</option>
                                    <option value="1">Scène 1 Standard</option>
                                    <option value="2">Scène 2 Principale</option>
                                    <option value="3">Scène 3 Principale</option>
                                    <option value="4">Studio Premium</option>
                                </select>
                                </div>
                            <div class="form-control sm:max-w-xl" style="margin: 5px;">
                                <textarea type="text" class=" md:max-w-2xl outline-none border-2 border-transparent focus:border-primary bg-body text-gray-600 dark:text-gray-200 rounded-3xl px-6 py-3 w-full">
                                    Donnez plus de détails sur votre réservation et votre fiche technique    
                                </textarea>
                            </div>

                            <div class="form-control sm:max-w-xl" style="margin-top: 15px;">
                                <input type="number" disabled placeholder="TOTAL A PAYER ----- FCFA" min="1" class=" md:max-w-2xl outline-none border-2 border-transparent focus:border-primary bg-body text-gray-600 dark:text-gray-200 rounded-3xl px-6 py-3 w-full">
                            </div>
                            <div
                                class="sm:inline-flex sm:min-w-max absolute sm:relative top-0.5 right-0.5 sm:top-0 sm:right-0" style="margin: 5px;">
                                <button
                                    class="min-w-max p-3 sm:py-3 sm:px-6 text-white border-2 border-transparent relative group">
                                    <span
                                        class="absolute inset-0 rounded-full group-hover:scale-105 origin-center transition-all ease-in-out bg-primary"></span>
                                    <span aria-hidden="true" class="relative hidden sm:flex">
                                        Finaliser la réservation
                                    </span>
                                    <span class="relative flex sm:hidden">
                                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                            stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
                                            <path stroke-linecap="round" stroke-linejoin="round"
                                                d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5" />
                                        </svg>
                                    </span>
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </AtomsContainer>
    </section>
</template>