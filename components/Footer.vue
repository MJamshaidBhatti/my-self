<template>
  <!-- <section
    class="relative isolate overflow-hidden bg-gray-900 px-6 py-15 sm:py-20 lg:px-8"
  >
    <div class="mx-auto max-w-2xl lg:max-w-4xl">
      <img
        class="mx-auto h-12"
        src="https://tailwindui.com/img/logos/workcation-logo-indigo-600.svg"
        alt=""
      />
      <figure class="mt-10">
        <blockquote
          class="text-center text-xl font-semibold leading-8 text-white sm:text-2xl sm:leading-9"
        >
          <p>
            “Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo
            expedita voluptas culpa sapiente alias molestiae. Numquam corrupti
            in laborum sed rerum et corporis.”
          </p>
        </blockquote>
        <figcaption class="mt-10">
          <img
            class="mx-auto h-10 w-10 rounded-full"
            src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
            alt=""
          />
          <div
            class="mt-4 flex items-center justify-center space-x-3 text-base"
          >
            <div class="font-semibold text-white">Judith Black</div>
            <svg
              viewBox="0 0 2 2"
              width="3"
              height="3"
              aria-hidden="true"
              class="fill-gray-900"
            >
              <circle cx="1" cy="1" r="1" />
            </svg>
            <div class="text-white">CEO of Workcation</div>
          </div>
        </figcaption>
      </figure>
    </div>
  </section> -->
  <div class="cantainer-fluid bg-gray-900 py-20">
    <div class="grid border-gray-700 md:grid-cols-2">
      <figure
        class="border-0 border-gray-600 flex flex-col items-center justify-center text-center rounded-t-lg md:rounded-t-none md:rounded-tl-lg dark:bg-gray-900"
      >
        <blockquote class="max-w-2xl mx-auto dark:text-gray-400">
          <div class="flex items-center justify-between flex-col">
            <img
              class="h-14 w-auto logo-action"
              src="../assets/img/tayyab4.png"
              alt="Your Company"
            />
            <!-- <img
              class="mx-auto h-10 w-10 rounded-full"
              src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
              alt=""
            /> -->
            <h3 class="text-sm lg:text-xl font-semibold dark:text-white">
              Developer Neede
            </h3>
          </div>

          <p class="my-4 font-light px-4leading-relaxed">
            Tayyab did a great job during our short collaboration with him. He
            is a talented developer.
          </p>
        </blockquote>

        <div class="flex items-center justify-center flex-wrap footer-action">
          <div class="Marquee-tag flex flex-col">
            <a
              href="https://www.linkedin.com/in/muhammad-tayyab-manzoor-8b0224193/
"
            >
              <img
                src="https://seeklogo.com/images/L/linkedin-icon-logo-05B2880899-seeklogo.com.png"
                alt="Vue.js"
              />
            </a>
            <!-- <h3 class="pt-4 text-sm font-medium">Vue.js</h3> -->
          </div>
          <div class="Marquee-tag flex flex-col">
            <a href="https://github.com/datafast01">
              <img
                src="https://seeklogo.com/images/G/github-logo-2E3852456C-seeklogo.com.png"
                alt="Nuxt.js"
              />
            </a>
            <!-- <h3 class="pt-4 text-sm font-medium">Nuxt.js</h3> -->
          </div>
          <div class="Marquee-tag flex flex-col">
            <a href="https://www.upwork.com/freelancers/~011b27414e6fe369b1">
              <img
                src="https://seeklogo.com/images/U/upwork-logo-38004EEA61-seeklogo.com.png"
                alt="Javascript"
              />
            </a>
            <!-- <h3 class="pt-4 text-sm font-medium">Javascript</h3> -->
          </div>
          <!-- <div class="Marquee-tag flex flex-col">
            <img
              src="https://seeklogo.com/images/H/html5-logo-EF92D240D7-seeklogo.com.png"
              alt="HTML"
            />
             <h3 class="pt-4 text-sm font-medium">HTML</h3> 
          </div> -->
        </div>

        <figcaption class="flex items-center justify-center">
          <div class="font-medium">
            <div>Jonathan Snyders</div>
            <div
              class="text-sm font-light text-gray-500 dark:text-gray-400 italic"
            >
              Operations at MoonBird
            </div>
          </div>
        </figcaption>
      </figure>

      <Form />
    </div>
  </div>
</template>
<style scoped>
.footer-action .Marquee-tag {
  align-items: center;
  border-radius: 50px !important;
  display: inline-flex;
  height: 97px;
  justify-content: center;
  margin: 0 1em;
  padding: 0.5em;
  transition: all 0.5s ease-in-out;
  width: 77px;
}
.footer-action .Marquee-tag img {
  border-radius: 50px !important;
}
</style>
