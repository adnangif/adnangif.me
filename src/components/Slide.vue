<template>
  <div v-for="{ image, description } in perks" class="mt-24">
    <div class="w-full flex-col justify-between">
      <div class="flex justify-center">
        <img class="w-60" :src="image" />
      </div>
      <p class="m-6 text-gray-500">{{ description }}</p>
    </div>
  </div>
</template>
<script setup>
const perks = [
  {
    image: "src/assets/undraw_Choose_re_7d5a.svg",
    description:
      "Build website with the least efford. Choose features to your liking",
  },
  {
    image: "src/assets/undraw_Sync_re_492g.svg",
    description: "Run your apps on multiple platforms without an worry.",
  },
  {
    image: "src/assets/undraw_portfolio_feedback_6r17.svg",
    description: "Showoff your works in your portfolio.",
  },
  {
    image: "src/assets/undraw_Push_notifications_re_t84m.svg",
    description: "Always be in touch and be notified about the progress.",
  },
  {
    image: "src/assets/undraw_Partying_re_at7f.svg",
    description: "Celebrate your success with the world.",
  },
];
</script>
