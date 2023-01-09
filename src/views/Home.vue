<script setup lang="ts">
</script>

<template>
  <main>
    <h1 class="text-6xl"> Sas a quello stronzo </h1>
    <p class="text-base"> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Alias, optio
      repudiandae necessitatibus quidem vitae quia non! Ducimus ipsa et tempora!
    </p>
  </main>
</template>


<style>
button {
  --btn-main-clr: theme('colors.gray.200');
  --btn-accent-clr: theme('colors.gray.300');
  --btn-contrast-clr: theme('colors.gray.800');

  color: var(--btn-contrast-clr);
  background-color: var(--btn-main-clr);

  @apply inline-flex gap-2 leading-[48px] px-6 font-medium rounded-lg;

  transition: all .25s cubic-bezier(0.215, 0.610, 0.355, 1);
}

button:hover {
  --btn-main-clr: theme('colors.gray.300');
}
</style>