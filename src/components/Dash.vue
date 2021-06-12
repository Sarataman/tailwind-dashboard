<template>
  <div class="antialiased bg-gray-50 text-black lg:w-full">
    <div class="bg-white">
      <header class="space-y-2">
        <SiteHeader/>
      </header>
    </div>
    <div class="border-t border-gray-200 pb-10 w-full">
      <main class="mx-auto pb-1 lg:hidden xl:grid xl:grid-cols-12 xl:col-gap-20">
        <div class="xl:col-span-9 lg:w-full">
          <div class="col-span-2 px-6 xl:pl-9 w-full">
            <div class="xl:flex xl:items-center mt-9">
              <div class="flex w-full">
                <div class="flex items-center px-0">
                  <img class="h-14 w-14 rounded-full" src="../assets/profile.jpg" alt="profile picture">
                </div>
                <div class="flex flex-col block ml-2 justify-between">
                  <div class="flex items-center">
                    <h1 class="text-md font-semibold leading-none text-gray-800">Sarah Ataman</h1>
                  </div>
                  <div class="flex text-md text-gray-500 font-medium mt-2">
                    <span class="pr-2">
                      <img src="../assets/github.png" alt="" class="h-7 w-7 opacity-40">
                    </span>
                    sarataman
                  </div>
                </div>
              </div>
              <div class="hidden lg:flex lg:w-full lg:justify-end lg:-ml-4">
                <a href="" class="flex items-center justify-center rounded-md border border-gray-300 bg-indigo-700 mt-6 xl:my-2 my-2 h-12 leading-5 font-medium text-gray-200 hover:border-indigo-900 hover:text-black shadow-sm px-6 xl:mx-2">New Project</a>
                <a href="" class="flex items-center justify-center rounded-md border border-gray-300 bg-white my-2 h-12 leading-5 font-medium text-gray-800 hover:border-indigo-900 hover:text-black hover:bg-white shadow-sm px-6 xl:mx-4">Invite Team</a>
              </div>
            </div>
            <div class="grid md:flex lg:hidden">
              <a href="" class="flex items-center justify-center rounded-md border border-gray-300 bg-indigo-700 mt-6 my-2 h-12 leading-5 font-medium text-gray-200 hover:border-indigo-900 hover:text-black shadow-sm md:w-52 xl:px-4">New Project</a>
              <a href="" class="flex items-center justify-center rounded-md border border-gray-300 bg-white my-2 h-12  leading-5 font-medium text-gray-800 hover:border-indigo-900 hover:text-black hover:bg-white shadow-sm md:w-52 md:mt-6 md:mx-5 xl:px-4">Invite Team</a>
            </div>
            <div class="text-gray-500">
              <div class="my-4 flex">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 opacity-70" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                  </svg>
                  <span class="ml-2">
                    Pro Member
                  </span>
              </div>
              <div class="my-4 flex">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 opacity-70" viewBox="0 0 20 20" fill="currentColor">
                  <path d="M7 3a1 1 0 000 2h6a1 1 0 100-2H7zM4 7a1 1 0 011-1h10a1 1 0 110 2H5a1 1 0 01-1-1zM2 11a2 2 0 012-2h12a2 2 0 012 2v4a2 2 0 01-2 2H4a2 2 0 01-2-2v-4z" />
                </svg>
                <span class="ml-2">
                  8 Projects
                </span>
              </div>
            </div>
          </div>
          <div class="col-span-7 border-l border-t border-r border-gray-200">
            <div class="lg:mt-6 lg:w-full min-w-full">
              <div class="flex justify-between mx-7 xl:mx-7 xl:mr-9 py-5 lg:py-2 lg:mb-4 lg:px-3">
                <h2 class="text-lg font-semibold">
                Projects
                </h2>
                <a href="#" class="flex border border-gray-300 shadow-sm rounded-lg px-3 py-2 text-md font-semibold text-gray-900 leading-5 hover:border-black transition ease-in-out duration-150">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 opacity-40" viewBox="0 0 20 20" fill="currentColor">
                    <path d="M3 3a1 1 0 000 2h11a1 1 0 100-2H3zM3 7a1 1 0 000 2h5a1 1 0 000-2H3zM3 11a1 1 0 100 2h4a1 1 0 100-2H3zM13 16a1 1 0 102 0v-5.586l1.293 1.293a1 1 0 001.414-1.414l-3-3a1 1 0 00-1.414 0l-3 3a1 1 0 101.414 1.414L13 10.414V16z" />
                  </svg>
                  <span class="px-3">
                    Sort
                  </span>
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 opacity-40" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                  </svg>
                </a>
              </div>
              <div>
                <ProjectCard/>
              </div>
            </div>
          </div>
        </div>
        <div class="col-span-3 bg-gray-100 :col-span-12 lg:col-span-3 min-w-full">
          <div class="px-7 sm:pl-10 pt-9 pr-10">
            <h2 class="text-md font-semibold">
              Activity
            </h2>
              <ActivityFeedItem/>
          </div>
        </div>
      </main>
      <main class="hidden mx-auto pb-1 -px-3 lg:grid lg:grid-cols-12 lg:col-gap-20 lg:pl-5 xl:hidden">
        <div class="col-span-2 px-3 pl-2 text-sm">
          <div class="flex items-center mt-9">
            <div class="flex">
              <div class="flex items-center px-0">
                <img class="h-12 w-12 rounded-full" src="../assets/profile.jpg" alt="profile picture">
              </div>
              <div class="flex flex-col block ml-2 justify-between">
                <div class="flex items-center">
                  <h1 class="font-semibold leading-none text-gray-800">Sarah Ataman</h1>
                </div>
                <div class="flex text-gray-500 font-medium mt-2 w-full">
                  <span class="">
                    <img src="../assets/github.png" alt="" class="h-7 w-7 opacity-40">
                  </span>
                  sarataman
                </div>
              </div>
            </div>
          </div>
          <div class="grid">
            <a href="" class="flex items-center justify-center rounded-md border border-gray-300 bg-indigo-700 mt-6 my-2 h-12 font-medium text-gray-200 hover:border-indigo-900 hover:text-black shadow-sm transition ease-in-out duration-150 px-3">New Project</a>
            <a href="" class="flex items-center justify-center rounded-md border border-gray-300 bg-white my-2 h-12 font-medium text-gray-800 hover:border-indigo-900 hover:text-black hover:bg-white shadow-sm transition ease-in-out duration-150 px-3">Invite Team</a>
          </div>
          <div class="text-gray-500">
            <div class="my-4 flex">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 opacity-70" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                </svg>
                <span class="ml-2">
                  Pro Member
                </span>
            </div>
            <div class="my-4 flex">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 opacity-70" viewBox="0 0 20 20" fill="currentColor">
                <path d="M7 3a1 1 0 000 2h6a1 1 0 100-2H7zM4 7a1 1 0 011-1h10a1 1 0 110 2H5a1 1 0 01-1-1zM2 11a2 2 0 012-2h12a2 2 0 012 2v4a2 2 0 01-2 2H4a2 2 0 01-2-2v-4z" />
              </svg>
              <span class="ml-2">
                8 Projects
              </span>
            </div>
          </div>
        </div>
        <div class="col-span-7 border-l border-t border-r border-gray-200 overflow-x-scroll overflow-y-scroll">
          <div class="sm:mt-6 min-w-max text-sm">
            <div class="flex justify-between mx-7 py-2">
              <h2 class="text-lg font-semibold">
              Projects
              </h2>
              <a href="#" class="flex border border-gray-300 shadow-sm rounded-lg px-3 py-2 text-md font-semibold text-gray-900 leading-5 hover:border-black transition ease-in-out duration-150">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 opacity-40" viewBox="0 0 20 20" fill="currentColor">
                  <path d="M3 3a1 1 0 000 2h11a1 1 0 100-2H3zM3 7a1 1 0 000 2h5a1 1 0 000-2H3zM3 11a1 1 0 100 2h4a1 1 0 100-2H3zM13 16a1 1 0 102 0v-5.586l1.293 1.293a1 1 0 001.414-1.414l-3-3a1 1 0 00-1.414 0l-3 3a1 1 0 101.414 1.414L13 10.414V16z" />
                </svg>
                <span class="px-3">
                  Sort
                </span>
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 opacity-40" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                </svg>
              </a>
            </div>
            <div>
              <ProjectCard/>
            </div>
          </div>
        </div>
        <div class="col-span-3 bg-gray-100 overflow-x-scroll overflow-y-scroll max-w-screen-xl text-sm">
          <div class="pl-5 pt-9 pr-8">
            <h2 class="font-semibold">
              Activity
            </h2>
              <ActivityFeedItem/>
          </div>
        </div>
      </main>
    </div>
  </div>
</template>

<script>
import SiteHeader from '@/components/SiteHeader'
import ProjectCard from '@/components/ProjectCard'
import ActivityFeedItem from '@/components/ActivityFeedItem'
// import AccountSwitcher from '@/components/AccountSwitcher'
export default {
  components: {
    SiteHeader,
    ProjectCard,
    ActivityFeedItem,
    // AccountSwitcher
    }
};
</script>

<style>
</style>