<template>
  <UContainer class="py-2">
    <div class="flex flex-row">
      <div class="flex flex-col w-64">
        <span class="text-gray-400 text-sm">2024, April</span>
        <UVerticalNavigation :links="links" />
      </div>

      <NuxtPage />
    </div>
  </UContainer>
</template>

<script setup lang="ts">
const links = [
  {label: "- Meaningful Activity", to: "/thoughts/meaningful-activity"},
  {label: "- Rage & Violence", to: "/thoughts/rage-violence"},
  {label: "- Admitting Defeat", to: "/thoughts/admitting-defeat"},
];
</script>