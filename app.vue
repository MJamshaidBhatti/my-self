<template>
  <div>
    <Header />
    <NuxtPage />
    <Footer />
  </div>
</template>
<style>
body {
  background-color: black;
}
.page-enter-active,
.page-Leave-active {
  transition: all 0.4s;
}

.page-enter-active,
.page-Leave-active {
  opacity: 0;
  filter: blur(1rem);
}
</style>
