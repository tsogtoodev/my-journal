<template>
  <UContainer class="py-2">
    <div class="flex flex-row">
      <div class="flex flex-col w-64">
        <span class="text-gray-400 text-sm">2024, April</span>
        <UVerticalNavigation :links="april2024" />
      </div>

      <NuxtPage />
    </div>
  </UContainer>
</template>

<script setup lang="ts">
const april2024 = [
  {label: "- 6th", to: "/diary/d-2024-04-06"},
];
</script>