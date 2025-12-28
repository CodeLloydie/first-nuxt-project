<template>
  <NuxtRouteAnnouncer />
  
  <div class="p-8 space-y-6">
    <!-- Inline styles to verify the element renders -->
    <h1 style="color: red; font-size: 40px;">
      Test 1: Inline styles (should be red)
    </h1>
    
    <!-- Tailwind classes -->
    <h1 class="text-blue-500 text-4xl font-bold">
      Test 2: Tailwind classes (should be blue)
    </h1>
    
    <!-- Regular HTML button with Tailwind classes -->
    <div class="space-y-2">
      <p class="font-semibold">Regular HTML Button (with Tailwind):</p>
      <button class="bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600">
        Test 3A: Regular Button
      </button>
    </div>

    <!-- Nuxt UI component -->
    <div class="space-y-2">
      <p class="font-semibold">Nuxt UI Button Component:</p>
      <UButton>
        Test 3B: Nuxt UI Button
      </UButton>
    </div>
  </div>
</template>