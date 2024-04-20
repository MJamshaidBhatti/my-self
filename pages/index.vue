<template>
  <div class="dark:accent-slate-900 pt-16 sm:pt-0">
    <section
      class="container-fluid mx-auto bg-gray-950 flex flex-col md:flex-row px-10 overflow-x-hidden"
    >
      <div class="w-full md:w-2/4 mt-12 md:mt-32 order-last md:order-first">
        <Transition
          enter-active-class="animate__animated animate__lightSpeedInLeft"
        >
          <h1
            v-if="show"
            class="text-4xl md:text-3xl lg:text-5xl xl:text-7xl font-medium hero-text flex flex-wrap"
          >
            <span class="mr-4 word-down"><span class="">I</span></span>
            <span class="mr-4 word-down"><span class="">create</span></span>
            <span class="mr-4 word-down"><span class="">digital</span></span>
            <span class="mr-4 word-down"
            ><span class="">experiences</span></span
            >
            <span class="mr-4 word-down"><span class="">that</span></span>
            <span class="mr-4 word-down"><span class="">make</span></span>
            <span class="mr-4 word-down"><span class="">an</span></span>
            <span class="mr-4 word-down">
              <span
                class="text-transparent bg-clip-text bg-gradient-to-r from-purple-100 to-pink-400"
              >
                impact.</span
              >
            </span>
          </h1>
        </Transition>

        <Transition enter-active-class="animate__animated animate__bounceIn">
          <h2 v-if="show" class="flex flex-wrap mt-16">
            <span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">A</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">developer</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">with</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">bachelors</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">degree</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">in</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">CS</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">and</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">a</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">passion</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">for</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">turning</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">ideas</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">into</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">reality</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">through</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">code.</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">With</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">15+</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">large</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">successful</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">projects</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">under</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">my</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">belt,</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">I</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">specialize</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">in</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span
                class="italic font-bolder text-transparent bg-clip-text bg-gradient-to-r from-purple-100 to-pink-400 font-extrabold"
                >full</span
              ></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span
                class="italic font-bolder text-transparent bg-clip-text bg-gradient-to-r from-purple-100 to-pink-400 font-extrabold"
                >stack</span
              ></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span
                class="italic font-bolder text-transparent bg-clip-text bg-gradient-to-r from-purple-100 to-pink-400 font-extrabold"
                >development</span
              ></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">with</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span
                class="italic font-bolder text-transparent bg-clip-text bg-gradient-to-r from-purple-100 to-pink-400 font-extrabold"
                >UI/UX</span
              ></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">design.</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">Let's</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">build</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">something</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">great</span></span
            ><span class="mr-2 text-md md:text-md word-opacity"
              ><span class="italic">together!</span></span
            >
          </h2>
        </Transition>

        <div class="my-10 md:mt-10 flex">
          <a href="https://github.com/datafast01" class="mr-3"
            ><img
              class="contact-logo word-down rounded"
              src="https://seeklogo.com/images/G/github-colored-logo-FDDF6EB1F0-seeklogo.com.png" /></a
          ><a href="mailto:tayyab.manzoor02@gmail.com" class="mr-3"
            ><img
              class="contact-logo word-down"
              src="https://seeklogo.com/images/G/gmail-new-2020-logo-32DBE11BB4-seeklogo.com.png"
          />
        </a>
        </div>
      </div>
      <div
        class="hidden md:flex md:w-2/4 order-first md:order-last overflow-hidden"
      >
        <Transition
          enter-active-class="animate__animated animate__jackInTheBox"
        >
          <div v-if="show">
            <img
              class="img animate-pulse"
              src="../assets/img/banner.svg"
              height="0"
              alt="CodeWithBazzyHeroImage"
            />
          </div>
        </Transition>
      </div>
    </section>

    <div class="Marquee bg-gray-950">
      <div class="Marquee-content-left">
        <!--[-->
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/V/vuejs-logo-17D586B587-seeklogo.com.png"
            alt="Vue.js"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Vue.js</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/N/nuxt-logo-D5098E139E-seeklogo.com.png"
            alt="Nuxt.js"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Nuxt.js</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/J/javascript-logo-8892AEFCAC-seeklogo.com.png"
            alt="Javascript"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Javascript</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/H/html5-logo-EF92D240D7-seeklogo.com.png"
            alt="HTML"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">HTML</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/C/css3-logo-8724075274-seeklogo.com.png"
            alt="CSS"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">CSS</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/R/react-logo-7B3CE81517-seeklogo.com.png"
            alt="React.js"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">React.js</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/R/redux-logo-9CA6836C12-seeklogo.com.png"
            alt="Redux"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Redux</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/S/sass-logo-EFE1469B2C-seeklogo.com.png"
            alt="Sass"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Sass</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/V/vuetify-logo-3BCF73C928-seeklogo.com.png"
            alt="Vuetify"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Vuetify</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/T/tailwind-css-logo-5AD4175897-seeklogo.com.png"
            alt="Tailwind css"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Tailwind css</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/T/typescript-logo-B29A3F462D-seeklogo.com.png"
            alt="TypeScript"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">TypeScript</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/N/nodejs-logo-54107C5EDD-seeklogo.com.png"
            alt="Node.js"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Node.js</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/R/redis-logo-E403D4DD6A-seeklogo.com.png"
            alt="Redis"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Redis</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/F/figma-logo-E4E21D3AEA-seeklogo.com.png"
            alt="Figma"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Figma</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/M/mongodb-logo-4A71340576-seeklogo.com.png"
            alt="Mongo DB"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Mongo DB</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/G/git-logo-CD8D6F1C09-seeklogo.com.png"
            alt="Git"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Git</h3>
        </div>
        <!--]-->
      </div>
    </div>

    <div class="container-fluid p-8 bg-gray-950 mx-0">
      <div
        class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-4 xl:grid-cols-4 gap-6"
      >
        <!--[-->
        <div
          class="card p-6 rounded-lg shadow bg-gray-900"
          style="opacity: 1; transform: translateX(0px)"
        >
          <div class="flex justify-center">
            <img
              src="https://cdn-icons-png.flaticon.com/512/3159/3159301.png"
              class="logo"
              alt="Frontend Development"
              style="opacity: 1; transform: translateX(0px)"
            />
          </div>
          <h5
            class="my-3 text-center text-xl md:text-xl lg:2xl font-medium tracking-tight dark:text-white"
          >
            Frontend Development
          </h5>
          <p
            class="text-center text-sm md:text-md mt-10 font-normal dark:text-gray-400"
          >
            Crafting immersive digital experiences through innovative frontend
            development.
          </p>
        </div>
        <div
          class="card p-6 rounded-lg shadow bg-gray-900"
          style="opacity: 1; transform: translateX(0px)"
        >
          <div class="flex justify-center">
            <img
              src="https://cdn-icons-png.flaticon.com/512/8635/8635374.png"
              class="logo"
              alt="Backend Development"
              style="opacity: 1; transform: translateX(0px)"
            />
          </div>
          <h5
            class="my-3 text-center text-xl md:text-xl lg:2xl font-medium tracking-tight dark:text-white"
          >
            Backend Development
          </h5>
          <p
            class="text-center text-sm md:text-md mt-10 font-normal dark:text-gray-400"
          >

            Empowering digital infrastructure through efficient and scalable
            backend development.

          </p>
        </div>
        <div
          class="card p-6 rounded-lg shadow bg-gray-900"
          style="opacity: 1; transform: translateX(0px)"
        >
          <div class="flex justify-center">
            <img
              src="https://cdn-icons-png.flaticon.com/512/7858/7858975.png"
              class="logo"
              alt="UI/UX"
              style="opacity: 1; transform: translateX(0px)"
            />
          </div>
          <h5
            class="my-3 text-center text-xl md:text-xl lg:2xl font-medium tracking-tight dark:text-white"
          >
            UI/UX
          </h5>
          <p
            class="text-center text-sm md:text-md mt-10 font-normal dark:text-gray-400"
          >
            Designing intuitive and engaging digital experiences that delight
            users.
          </p>
        </div>
        <div
          class="card p-6 rounded-lg shadow bg-gray-900"
          style="opacity: 1; transform: translateX(0px)"
        >
          <div class="flex justify-center">
            <img
              src="https://cdn-icons-png.flaticon.com/512/2888/2888125.png"
              class="logo"
              alt="Mentorship"
              style="opacity: 1; transform: translateX(0px)"
            />
          </div>
          <h5
            class="my-3 text-center text-xl md:text-xl lg:2xl font-medium tracking-tight dark:text-white"
          >
            Mentorship
          </h5>
          <p
            class="text-center text-sm md:text-md mt-10 font-normal dark:text-gray-400"
          >
            Empowering the next generation of leaders through personalized
            guidance and mentorship.
          </p>
        </div>
        <!--]-->
      </div>
    </div>

    <section class="Marquee bg-gray-950">
      <div class="Marquee-content-right">
        <!--[-->
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/V/vuejs-logo-17D586B587-seeklogo.com.png"
            alt="Vue.js"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Vue.js</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/N/nuxt-logo-D5098E139E-seeklogo.com.png"
            alt="Nuxt.js"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Nuxt.js</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/J/javascript-logo-8892AEFCAC-seeklogo.com.png"
            alt="Javascript"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Javascript</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/H/html5-logo-EF92D240D7-seeklogo.com.png"
            alt="HTML"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">HTML</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/C/css3-logo-8724075274-seeklogo.com.png"
            alt="CSS"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">CSS</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/R/react-logo-7B3CE81517-seeklogo.com.png"
            alt="React.js"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">React.js</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/R/redux-logo-9CA6836C12-seeklogo.com.png"
            alt="Redux"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Redux</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/S/sass-logo-EFE1469B2C-seeklogo.com.png"
            alt="Sass"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Sass</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/V/vuetify-logo-3BCF73C928-seeklogo.com.png"
            alt="Vuetify"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Vuetify</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/T/tailwind-css-logo-5AD4175897-seeklogo.com.png"
            alt="Tailwind css"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Tailwind css</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/T/typescript-logo-B29A3F462D-seeklogo.com.png"
            alt="TypeScript"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">TypeScript</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/N/nodejs-logo-54107C5EDD-seeklogo.com.png"
            alt="Node.js"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Node.js</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/R/redis-logo-E403D4DD6A-seeklogo.com.png"
            alt="Redis"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Redis</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/F/figma-logo-E4E21D3AEA-seeklogo.com.png"
            alt="Figma"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Figma</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/M/mongodb-logo-4A71340576-seeklogo.com.png"
            alt="Mongo DB"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Mongo DB</h3>
        </div>
        <div class="Marquee-tag flex flex-col">
          <img
            src="https://seeklogo.com/images/G/git-logo-CD8D6F1C09-seeklogo.com.png"
            alt="Git"
          />
          <h3 class="pt-4 text-sm md:text-lg font-medium">Git</h3>
        </div>
        <!--]-->
      </div>
    </section>

    <div class="container-fluid bg-gray-950 m-0 p-8">
      <h1 class="text-xl md:text-4xl font-medium hero-text flex flex-wrap">
        <!--[--><span
          class="mr-2 md:mr-3 title-letter"
          style="transform: translateX(0px); opacity: 1"
          >Work</span
        ><span
          class="mr-2 md:mr-3 title-letter"
          style="transform: translateX(0px); opacity: 1"
          >Experience</span
        ><!--]-->
      </h1>
      <h4 class="text-xl italic my-2 pl-1 font-semibold">
        6+ years of overall experience
      </h4>
      <div class="pl-3 mt-16">
        <ol class="relative border-l border-gray-200 dark:border-gray-700">
          <!--[-->
          <li class="mb-10 ml-6">
            <span
              class="absolute flex items-center justify-center w-6 h-8 bg-blue-100 rounded-full -left-3 ring-8 ring-white dark:ring-gray-900 dark:bg-blue-900"
              ><svg
                aria-hidden="true"
                class="w-3 h-3 text-blue-800 dark:text-blue-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </span>
            <div class="ml-1 md:ml-4">
              <h3
                class="flex items-center mb-1 text-sm sm:text-lg md:text-2xl font-semibold dark:text-white"
              >
                Vue Js | React Js | Javascript Developer
                <span
                  class="bg-blue-100 text-blue-800 hidden md:flex text-sm font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-blue-900 dark:text-blue-300 ml-3"
                >
                  Currently working here
                </span>
              </h3>
              <i><a href="https://upwork.com">Upwork</a></i
              ><time
                class="block my-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
                >Dec 2020 - Present</time
              >
              <p
                class="mb-4 text-sm font-normal text-gray-200 dark:text-gray-400 leading-8"
              >
                - TOP RATED freelancer on upwork - Top 10% among the talent on
                upwork. <br />
                - Worked on more than 15+ mid to large scale projects with 5
                star exceptional feedbacks by clients from USA, UK, Bulgaria,
                Germany, Australia, Switzerland. <br />
              </p>
            </div>
          </li>
          <li class="mb-10 ml-6">
            <span
              class="absolute flex items-center justify-center w-6 h-8 bg-blue-100 rounded-full -left-3 ring-8 ring-white dark:ring-gray-900 dark:bg-blue-900"
              ><svg
                aria-hidden="true"
                class="w-3 h-3 text-blue-800 dark:text-blue-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </span>
            <div class="ml-1 md:ml-4">
              <h3
                class="flex items-center mb-1 text-sm sm:text-lg md:text-2xl font-semibold dark:text-white"
              >
                Full Stack Developer
                <!---->
              </h3>
              <i><a href="https://parket.co.za">GetScaled.Inc</a></i
              ><time
                class="block my-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
                >June 2023 - Present</time
              >
              <p
                class="mb-4 text-sm font-normal text-gray-200 dark:text-gray-400 leading-8"
              >
                - Involved in designing, developing and testing internal
                dashboards used by companies stakeholders, landlords and
                management. <br />
                - Developing efficient searching on tables with large data using
                indexed db, leveraging the use of web workers for searches.
                <br />
                - Converted Figma/XD designs into pixel perfect presentations
                with attention to detail and high quality code design. <br />
                - Making sure the application bundle size is as minimum as
                possible, treeshaking components, lazy loading for performance.
              </p>
            </div>
          </li>
          <li class="mb-10 ml-6">
            <span
              class="absolute flex items-center justify-center w-6 h-8 bg-blue-100 rounded-full -left-3 ring-8 ring-white dark:ring-gray-900 dark:bg-blue-900"
              ><svg
                aria-hidden="true"
                class="w-3 h-3 text-blue-800 dark:text-blue-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </span>
            <div class="ml-1 md:ml-4">
              <h3
                class="flex items-center mb-1 text-sm sm:text-lg md:text-2xl font-semibold dark:text-white"
              >
                Vue.js Developer
                <!---->
              </h3>
              <i><a href="https://sonicwall.com">Developers Studio</a></i
              ><time
                class="block my-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
                >July 2022 - June 2023</time
              >
              <p
                class="mb-4 text-sm font-normal text-gray-200 dark:text-gray-400 leading-8"
              >
                - Part of the Research &amp; Development (R&amp;D) team working
                on improving the client facing as well as internal products.
                <br />
                - Migration of Legacy Projects To Latest JS Frameworks
                (Migrating Legacy ng files code to .vue files). <br />
                - Creating Dashboards to depict large amounts of data into
                charts and graphs.
              </p>
            </div>
          </li>
          <li class="mb-10 ml-6">
            <span
              class="absolute flex items-center justify-center w-6 h-8 bg-blue-100 rounded-full -left-3 ring-8 ring-white dark:ring-gray-900 dark:bg-blue-900"
              ><svg
                aria-hidden="true"
                class="w-3 h-3 text-blue-800 dark:text-blue-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </span>
            <div class="ml-1 md:ml-4">
              <h3
                class="flex items-center mb-1 text-sm sm:text-lg md:text-2xl font-semibold dark:text-white"
              >
                Frontend Developer
                <!---->
              </h3>
              <i
                ><a href="https://www.linkedin.com/company/modistabox/"
                  >AWAYR</a
                ></i
              ><time
                class="block my-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
                >Sep 2020 - June 2022</time
              >
              <p
                class="mb-4 text-sm font-normal text-gray-200 dark:text-gray-400 leading-8"
              >
                - Developing new user-interfaces using Vue Js. and React Js
                <br />
                - Building Reusable Components and Front End Libraries For
                Future Use. <br />
                - Translating Adobe XD Designs And Wireframes Into High Quality
                Code. <br />
                - Optimizing Components For Maximum Performance Across Vast
                Array Of Web-Capable Devices And Browsers. <br />
              </p>
            </div>
          </li>
          <!--]-->
        </ol>
      </div>
    </div>

    <div class="container-fluid bg-gray-950 m-0 p-8">
      <!-- <div class="text-center max-w-xl mx-auto">
        <h1 class="text-2xl md:text-4xl mb-5 text-white">
          What People Are Saying
        </h1>
        <div class="text-center mb-10">
          <span class="inline-block w-1 h-1 rounded-full bg-white ml-1"></span
          ><span class="inline-block w-3 h-1 rounded-full bg-white ml-1"></span
          ><span class="inline-block w-40 h-1 rounded-full bg-white ml-1"></span
          ><span class="inline-block w-3 h-1 rounded-full bg-white ml-1"></span
          ><span class="inline-block w-1 h-1 rounded-full bg-white ml-1"></span>
        </div>
      </div> -->
      <div class="grid mb-8 gap-8 rounded-lg shadow-sm md:mb-12 md:grid-cols-2">
        <div>
          <div class="text-center max-w-xl mx-auto">
            <h1 class="text-2xl md:text-4xl mb-5 text-white">
              What People Are Saying
            </h1>
            <div class="text-center mb-10">
              <span
                class="inline-block w-1 h-1 rounded-full bg-white ml-1"
              ></span
              ><span
                class="inline-block w-3 h-1 rounded-full bg-white ml-1"
              ></span
              ><span
                class="inline-block w-40 h-1 rounded-full bg-white ml-1"
              ></span
              ><span
                class="inline-block w-3 h-1 rounded-full bg-white ml-1"
              ></span
              ><span
                class="inline-block w-1 h-1 rounded-full bg-white ml-1"
              ></span>
            </div>
          </div>

          <figure
            class="border rounded border-gray-600 flex flex-col items-center justify-center p-8 text-center dark:bg-gray-900"
          >
            <blockquote
              class="max-w-2xl mx-auto mb-4 lg:mb-8 dark:text-gray-400"
            >
              <h3 class="text-sm lg:text-xl font-semibold dark:text-white">
                Quasar (Vue.js) frontend development
              </h3>
              <p class="my-4 font-light leading-relaxed">
                Tayyab is extremely professional and cooperative. He promptly
                answers all my questions and demonstrates a strong understanding
                of his work. His optimization of my websites has significantly
                improved the performance. Overall, Tayyab is an excellent
                freelancer and a great deal!
              </p>
            </blockquote>
            <figcaption class="flex items-center justify-center">
              <div class="font-medium">
                <div>Andreas Polzer</div>
                <div class="text-sm font-light dark:text-gray-400 italic">
                  Owner at a company in Germany
                </div>
              </div>
            </figcaption>
          </figure>

          <figure
            class="border mt-10 rounded border-gray-600 flex flex-col items-center justify-center p-8 text-center dark:bg-gray-900"
          >
            <blockquote
              class="max-w-2xl mx-auto mb-4 lg:mb-8 dark:text-gray-400"
            >
              <h3 class="text-sm lg:text-xl font-semibold dark:text-white">
                Finish a front end web app built in Vue JS
              </h3>
              <p class="my-4 font-light leading-relaxed">
                Tayyab delivered high-quality work on the project, and it was a
                pleasure to collaborate with him.
              </p>
            </blockquote>
            <figcaption class="flex items-center justify-center">
              <div class="font-medium">
                <div>Dominic Marshall</div>
                <div class="text-sm font-light dark:text-gray-400 italic">
                  Owner at a company in UK
                </div>
              </div>
            </figcaption>
          </figure>
        </div>
        <div>
          <figure
            class="border rounded border-gray-600 flex flex-col items-center justify-center p-8 text-center dark:bg-gray-900"
          >
            <blockquote
              class="max-w-2xl mx-auto mb-4 lg:mb-8 dark:text-gray-400"
            >
              <h3 class="text-sm lg:text-xl font-semibold dark:text-white">
                PWA, vue.js, frontend devoloping
              </h3>
              <p class="my-4 font-light leading-relaxed">
                Well done! Tayyab has good communication skills, is engaged,
                team orientated, and an experienced developer. I already started
                a new contract with him.
              </p>
            </blockquote>
            <figcaption class="flex items-center justify-center">
              <div class="font-medium">
                <div>Richard Martin</div>
                <div class="text-sm font-light dark:text-gray-400 italic">
                  Owner at a company in Germany
                </div>
              </div>
            </figcaption>
          </figure>

          <figure
            class="border mt-10 rounded border-gray-600 flex flex-col items-center justify-center p-8 text-center dark:bg-gray-900"
          >
            <blockquote
              class="max-w-2xl mx-auto mb-4 lg:mb-8 dark:text-gray-400"
            >
              <h3 class="text-sm lg:text-xl font-semibold dark:text-white">
                Frontend with VUE JS
              </h3>
              <p class="my-4 font-light leading-relaxed">
                I recently worked with an exceptional freelancer Tayyab Manzoor
                who displayed remarkable skills in Vue.js development. His
                expertise was evident from the start as he understood our
                requirements and built a tailored solution that surpassed our
                expectations. Communication was seamless, with the freelancer
                being highly responsive and providing regular updates. Their
                professionalism and availability eliminated any obstacles,
                ensuring a smooth collaboration. What impressed me the most was
                his ability to create intuitive Vue.js components that resulted
                in a visually appealing, high-performing application. His
                commitment to quality assurance and meeting deadlines was
                commendable, making them a valuable asset to any project. In
                summary, I highly recommend this freelancer for their top-notch
                Vue.js development services. They exceeded expectations in every
                aspect and delivered outstanding results.
              </p>
            </blockquote>
            <figcaption class="flex items-center justify-center">
              <div class="font-medium">
                <div>Ivan Ivanov</div>
                <div class="text-sm font-light dark:text-gray-400 italic">
                  Owns a fintech startup
                </div>
              </div>
            </figcaption>
          </figure>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import banner from "../assets/img/banner.svg";
import "animate.css";
import { ref, onMounted } from "vue";
export default {
  setup() {
    const show = ref(false);

    onMounted(() => {
      // Set show to true after a short delay to allow the transition to play
      setTimeout(() => {
        show.value = true;
      }, 100);
    });

    return {
      show,
    };
  },
};
</script>

<style lang="scss" scoped></style>
