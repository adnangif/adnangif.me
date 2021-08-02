<template>
  <div v-for="{image,subtitle,description} in cardsList">
    <div class="m-8 mt-20 shadow-xl bg-blue-50 rounded-2xl">
      <div class="">
        <div
          class="
            flex
            justify-center
            py-16
            pb-16
            bg-gray-900
            border-white
            rounded-2xl
          "
        >
          <img class="w-32" :src="image" />
        </div>
      </div>
      <div class="pb-8 m-4 text-gray-400">
        <p class="mb-2 text-lg text-gray-700">{{ subtitle }}</p>
        <p>{{ description }}</p>
        hello
      </div>
    </div>
  </div>
</template>
<script setup>
const cardsList = [
  {
    image: require("../assets/alias.png"),
    subtitle: "Let's make the world a better place for everyone.",
    description:
      "We are a non profit orginization, trying to help the poor become economically independent.",
  },
  {
    image: require("../assets/forbay.png"),
    subtitle: "No one should suffer any injustice",
    description:
      "We are a non profit orginization, trying to help the poor become economically independent.",
  },
];
</script>
