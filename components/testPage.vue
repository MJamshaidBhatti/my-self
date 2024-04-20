<template>
  <Transition
    name="custom-classes"
    enter-active-class="animate__animated animate__tada"
    leave-active-class="animate__animated animate__bounceOutRight"
  >
    <p v-if="show">hello</p>
  </Transition>
</template>

<script>
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

<style>
/* Define custom animation classes here */
</style>
