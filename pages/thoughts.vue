<template>
  <UContainer class="py-2">
    <div class="flex flex-row">
      <div class="flex flex-col w-64 gap-4">
        <div class="flex flex-col gap-2">
          <span class="text-gray-400 text-sm">2025, February</span>
          <UVerticalNavigation :links="links2025February" />
        </div>

        <div class="flex flex-col gap-2">
          <span class="text-gray-400 text-sm">2024, April</span>
          <UVerticalNavigation :links="links2024April" />
        </div>
      </div>

      <NuxtPage />
    </div>
  </UContainer>
</template>

<script setup lang="ts">
const links2025February = [
  {label: "- Absolute Despair", to: "/thoughts/absolute-despair"},
];
const links2024April = [
  {label: "- Meaningful Activity", to: "/thoughts/meaningful-activity"},
  {label: "- Rage & Violence", to: "/thoughts/rage-violence"},
  {label: "- Admitting Defeat", to: "/thoughts/admitting-defeat"},
];
</script>