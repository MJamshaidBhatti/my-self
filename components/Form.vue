<template>
  <div>
    <form>
      <div class="space-y-12 px-12">
        <div class="card border rounded p-8 border-gray-600">
          <div class="grid grid-cols-1 gap-x-6 gap-y-8 sm:grid-cols-6">
            <div class="col-span-full">
              <label for="username" class="block text-sm font-medium leading-6"
                >Name</label
              >
              <div class="mt-2">
                <div
                  class="flex rounded-0 shadow-sm border-b focus-within:0 focus:0 focus-within:0 focus-visible:0 focus-within:0"
                >
                  <input
                    type="text"
                    name="username"
                    id="username"
                    class="block w-full flex-1 border-0 bg-transparent py-1.5 pl-1 focus:0 sm:text-sm sm:leading-6"
                    placeholder="name"
                  />
                </div>
              </div>
            </div>
            <div class="col-span-full">
              <label for="email" class="block text-sm font-medium leading-6"
                >Email address</label
              >
              <div class="mt-2 rounded-0 shadow-sm border-b">
                <input
                  id="email"
                  name="email"
                  type="email"
                  autocomplete="email"
                  class="block w-full rounded-md border-0 py-1.5 bg-transparent shadow-sm placeholder:text-gray-400 sm:text-sm sm:leading-6"
                />
              </div>
            </div>

            <div class="col-span-full">
              <label for="about" class="block text-sm font-medium leading-6"
                >About</label
              >
              <div class="mt-2 rounded-0 shadow-sm border-b">
                <textarea
                  id="about"
                  name="about"
                  rows="1"
                  class="block w-full rounded-0 bg-transparent border-0 py-1.5 sm:text-sm sm:leading-6"
                />
              </div>
            </div>
            <div class="col-span-full text-end">
              <button
                type="submit"
                class="rounded-md bg-indigo-500 px-3 py-2 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
              >
                Submit
              </button>
            </div>
          </div>
        </div>
      </div>
    </form>
  </div>
</template>

<script setup>
import { PhotoIcon, UserCircleIcon } from "@heroicons/vue/24/solid";
</script>
