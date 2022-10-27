<script setup lang="ts"></script>

<template>
  <figure class="bg-purple-300 border-l-8 border-purple-500 p-8 rounded-lg">
    <Icon name="bi:quote" size="48" class="-mx-2" />
    <blockquote class="text-lg">
      <slot />
    </blockquote>
    <figcaption class="italic text-sm mt-4">- Matt Maribojoc</figcaption>
  </figure>
</template>
