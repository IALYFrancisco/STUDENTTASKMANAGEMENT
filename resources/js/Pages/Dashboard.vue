<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight">Project</h2>
        </template>

        <div class="py-4">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <!-- <div class="bg-white dark:bg-gray-800 overflow-hidden shadow-sm sm:rounded-lg">
                    <div class="p-6 text-gray-900 dark:text-gray-100">You're logged in!</div>
                </div> -->
                <button class="mx-auto bg-green-500 hover:bg-green-400 text-white font-bold py-2 px-4 border-b-4 border-green-700 hover:border-green-500 rounded">
                    Create project
                </button>
            </div>
        </div>
        <!-- component -->
<div class="h-screen flex gap-4 items-center justify-center bg-white">

<!-- Card 1 -->
<a href="#" class="w-[25rem] border-2 border-b-4 border-gray-200 rounded-xl hover:bg-gray-50">

  <!-- Badge -->
  <p class="bg-sky-500 w-fit px-4 py-1 text-sm font-bold text-white rounded-tl-lg rounded-br-xl"> FEATURED </p>

  <div class="grid grid-cols-6 p-5 gap-y-2">

    <!-- Profile Picture -->
    <div>
      <img src="https://picsum.photos/seed/2/200/200" class="max-w-16 max-h-16 rounded-full" />
    </div>

    <!-- Description -->
    <div class="col-span-5 md:col-span-4 ml-4">

      <p class="text-sky-500 font-bold text-xs"> 20+ SPOTS LEFT </p>

      <p class="text-gray-600 font-bold"> [Intermediate/Advanced] Tea</p>

      <p class="text-gray-400"> Sat, Mar 12 . 7:00 - 8:30 AM </p>

      <p class="text-gray-400"> Beginner speakers </p>

    </div>

    <!-- Price -->
    <div class="flex col-start-2 ml-4 md:col-start-auto md:ml-0 md:justify-end">
      <p class="rounded-lg text-sky-500 font-bold bg-sky-100  py-1 px-3 text-sm w-fit h-fit"> $ 5 </p>
    </div>

  </div>

</a>

<!-- Card 2 -->
<a href="#" class="w-[25rem] border-2 border-b-4 border-gray-200 rounded-xl hover:bg-gray-50">
    <p class="bg-sky-500 w-fit px-4 py-1 text-sm font-bold text-white rounded-tl-lg rounded-br-xl"> FEATURED </p>

  <div class="grid grid-cols-6 p-5 gap-y-2">

    <!-- Profile Picture -->
    <div>
      <img src="https://picsum.photos/seed/2/200/200" class="max-w-16 max-h-16 rounded-full" />
    </div>

    <!-- Description -->
    <div class="col-span-5 md:col-span-4 ml-4">

      <p class="text-sky-500 font-bold text-xs"> 7+ SPOTS LEFT </p>

      <p class="text-gray-600 font-bold"> [Beginner] Light Discussion </p>

      <p class="text-gray-400"> Fri, Mar 11 . 8:00 - 9:30 AM </p>

      <p class="text-gray-400"> Beginner speakers </p>

    </div>

    <!-- Price -->
    <div class="flex col-start-2 ml-4 md:col-start-auto md:ml-0 md:justify-end">
      <p class="rounded-lg text-sky-500 font-bold bg-sky-100  py-1 px-3 text-sm w-fit h-fit"> FREE </p>
    </div>

  </div>

</a>

</div>
    </AuthenticatedLayout>
    
</template>