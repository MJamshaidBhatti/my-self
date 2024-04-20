<template>
  <div>
    <div class="dark:bg-black transition-colors">
      <!-- By default, you can have your project use whatever mode your OS is using. You can use "dark:{class}". You can also set your config to use a class instead of using your OS mode (WHICH IS WHAT I AM DOING HERE) -->
      <!-- Toggler -->
      <div
        class="bg-gray-500 w-20 mx-auto mt-10 cursor-pointer rounded-3xl toggler dark:bg-green-500"
      >
        <div
          class="bg-white w-10 h-10 scale-75 rounded-3xl transition-transform dark:bg-black"
        ></div>
      </div>
      <button @click="toggleDark()"></button>
      <!-- End Of Toggler -->

      <h1 class="text-center mt-4 font-bold dark:text-white">
        Dark Mode Toggler
      </h1>

      <div
        class="container mx-auto mt-10 bg-white dark:bg-slate-900 rounded-xl px-6 py-8 shadow-xl w-1/2 transition-colors"
      >
        <h3
          class="text-slate-900 dark:text-white font-medium tracking-tight transition-colors"
        >
          Lorem ipsum dolor sit.
        </h3>
        <p
          class="text-slate-500 dark:text-slate-400 mt-2 text-sm transition-colors"
        >
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque
          eius et mollitia laudantium. Facilis accusamus ipsa dolorum minima
          cupiditate. Libero cumque optio rerum molestias asperiores.
        </p>
      </div>
    </div>
  </div>
</template>
<script src="https://cdn.tailwindcss.com"></script>
<script setup>
tailwind.config = {
  darkMode: "class",
};
// Toggle Dark Functionality
let flag = true;
const toggler = document.querySelector(".toggler");

// Toggle Dark Function
const toggleDark = () => {
  toggler.addEventListener("click", () => {
    const html = document.documentElement;
    toggler.children[0].classList.toggle("translate-x-10");
    if (flag) {
      html.classList.add("dark");
    } else {
      html.classList.remove("dark");
    }
    flag = !flag;
  });
};
toggleDark();
</script>

<style lang="scss" scoped></style>
