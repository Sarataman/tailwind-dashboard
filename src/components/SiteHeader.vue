<template>
     <div class="flex flex-shrink-0 bg-indigo-700 w-full">
        <div class="w-full">
             <header class="sm:flex sm:items-center sm:justify-between sm:w-full">
                <div class="flex justify-between lg:grid lg:grid-cols-12 px-5 sm:px-0 py-2 xl:justify-center sm:w-full ">
                    <div class="flex items-center lg:col-span-2 xl:col-span-1 pl-2 sm:pl-7 xl:pl-8">
                        <svg
                            class="h-7 w-7"
                            viewBox="0 0 520 520"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                            >
                            <path
                                d="M187.432 271c-29.538 0-53.568 24.03-53.568 53.568v133.863c0 29.538 24.03 53.568 53.568 53.568C216.97 512 241 487.97 241 458.432V324.568C241 295.03 216.97 271 187.432 271z"
                                fill="#cacaf0"
                            />
                            <path
                                d="M103.863 271h-51.86c-28.596 0-51.86 23.265-51.86 51.86 0 28.596 23.265 51.86 51.86 51.86s51.86-23.265 51.86-51.86z"
                                fill="#cacaf0"
                            />
                            <path
                                d="M0 187.432C0 216.97 24.03 241 53.568 241h133.863C216.97 241 241 216.97 241 187.432s-24.03-53.568-53.568-53.568H53.568C24.03 133.863 0 157.894 0 187.432z"
                                fill="#cacaf0"
                            />
                            <path
                                d="M189.14 103.863H241v-51.86c0-28.596-23.265-51.86-51.86-51.86-28.596 0-51.86 23.265-51.86 51.86s23.264 51.86 51.86 51.86z"
                                fill="#cacaf0"
                            />
                            <path
                                d="M324.568 241c29.538 0 53.568-24.03 53.568-53.568V53.568C378.137 24.03 354.106 0 324.568 0S271 24.03 271 53.568v133.863C271 216.97 295.03 241 324.568 241z"
                                fill="#cacaf0"
                            />
                            <path
                                d="M408.137 241h51.86c28.596 0 51.86-23.265 51.86-51.86 0-28.596-23.265-51.86-51.86-51.86s-51.86 23.265-51.86 51.86z"
                                fill="#cacaf0"
                            />
                            <g fill="#cacaf0">
                                <path
                                d="M512 324.568C512 295.03 487.97 271 458.432 271H324.568C295.03 271 271 295.03 271 324.568s24.03 53.568 53.568 53.568h133.863c29.539.001 53.569-24.03 53.569-53.568z"
                                />
                                <path
                                d="M322.86 408.137H271v51.86c0 28.596 23.265 51.86 51.86 51.86 28.596 0 51.86-23.265 51.86-51.86s-23.264-51.86-51.86-51.86z"
                                />
                            </g>
                            </svg>
                    </div>
                    <div class="w-full lg:col-span-7 xl:col-span-8">
                        <div class="flex flex-1 sm:justify-between">
                            <div class="flex w-full sm:items-center">
                                <div class="relative w-full py-1 ml-2 sm:ml-12 lg:ml-10 xl:-ml-7 sm:mx-auto">
                                    <span class="absolute inset-y-0 left-0 flex items-center pl-4">
                                        <svg  class="h-4 w-4 text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                                        </svg>            
                                    </span>
                                    <input class="block pl-10 pr-4 py-2 w-full md:w-5/6 lg:w-full bg-indigo-600 rounded-md text-sm placeholder-gray-300 text-white focus:bg-white focus:placeholder-gray-700 focus:text-gray-900 focus:outline-none" placeholder="Search projects">
                                </div>
                            </div>
                        </div>    
                    </div>
                    <div class="flex justify-end sm:hidden">
                        <button @click="toggle" type="button" class="px-2 text-gray-300 hover:text-white">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 fill-current" viewBox="0 0 20 20">
                                <path v-if="isOpen" fill-rule="evenodd" clip-rule="evenodd" d="M18.278 16.864a1 1 0 0 1-1.414 1.414l-4.829-4.828-4.828 4.828a1 1 0 0 1-1.414-1.414l4.828-4.829-4.828-4.828a1 1 0 0 1 1.414-1.414l4.829 4.828 4.828-4.828a1 1 0 1 1 1.414 1.414l-4.828 4.829 4.828 4.828z"/>
                                <path v-if="!isOpen" fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />                            
                            </svg>
                        </button>
                    </div>
                    <div class="sm:w-full sm:flex sm:-mr-3 lg:ml-4 lg:col-span-3">
                        <div class="hidden sm:display sm:flex sm:justify-end px-3 w-full">
                            <button class="text-gray-300">
                                <a href="" class="px-2 inline-block text-sm hover:text-white leading-5">Documentation</a>
                                <a href="" class="px-2 inline-block text-sm hover:text-white leading-5">Support</a>
                            </button>
                            <Dropdown class="hidden sm:block sm:flex sm:items-center sm:pl-3">
                                <template #trigger="{ hasFocus, isOpen }">
                                    <span class="block h-7 w-7 overflow-hidden rounded-full"
                                        :class="[(hasFocus || isOpen) ? 'opacity-80' : 'border-none']"
                                    >
                                        <img class="h-full w-full object-cover" src="../assets/profile.jpg" alt="profile picture">
                                    </span>
                                </template>
                                <template #dropdown>
                                    <div class="mt-3 bg-white xl:border rounded-lg w-48 py-2 shadow-xl">
                                        <a href="#profile" class="block text-gray-400 hover:text-white text-gray-800 px-4 py-2 hover:bg-indigo-600">View Profile</a>
                                        <a href="#setting" class="block text-gray-400 hover:text-white text-gray-800 px-4 py-2 mt-0 hover:bg-indigo-600">Settings</a>
                                        <a href="#logout" class="block text-gray-400 hover:text-white text-gray-800 px-4 py-2 mt-0 hover:bg-indigo-600">Logout</a>
                                    </div>
                                </template>
                            </Dropdown>
                        </div>
                    </div>
                </div>
                <nav class="sm:flex items-center sm:px-4 flex-1 justify-between" :class="{ 'hidden': !isOpen, 'block': isOpen }">
                    <div class="items-center sm:hidden">
                        <div class="px-2 pt-2 pb-5 border-b border-indigo-800 sm:flex sm:border-b-0 sm:py-0 sm:text-sm sm:px-0">
                            <a href="#" class="block px-3 py-1.5 rounded-md text-gray-200 hover:bg-indigo-800 sm:px-2 xl:px-6 xl:text-gray-900 xl:hover:bg-gray-200">Documentation</a>
                            <a href="#" class="mt-1 sm:mt-0 px-3 py-1.5 rounded-md block text-gray-200 hover:bg-indigo-800 sm:px-2 sm:ml-2 xl:px-6 xl:text-gray-900 xl:hover:bg-gray-200">Support</a>
                        </div>
                        <div class="relative px-5 py-3 sm:py-0 sm:ml-4 sm:px-0">
                            <div class="sm:hidden">
                                <a href="#profile" class="block text-gray-200 hover:text-white">Your Profile</a>
                                <a href="#setting" class="mt-3 block text-gray-200 hover:text-white">Settings</a>
                                <router-link to="/">
                                <a href="#sign-out" class="mt-3 block text-gray-200 hover:text-white">Sign out</a>
                                </router-link>
                            </div>
                        </div>
                    </div>
                </nav>
            </header>
        </div>
    </div>
</template>

<script>
import Dropdown from '@/components/Dropdown'

export default {
    components: { Dropdown },
    props: [],
    data() {
        return {
        isOpen: false,
        }
    },
    methods: {
        toggle() {
            this.isOpen = !this.isOpen
        },
    },
}

</script>