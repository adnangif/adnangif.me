<template>
  <div class="relative text-gray-600 mt-20">
    <img class="bg-transparent-400" src="../assets/wave05.svg" alt="" />
    <div class="p-2 pt-0 bg-blue-300">
      <p class="font-semibold text-lg">Let's Talk</p>
      <label for="Email">Email</label><br /><input
        class="border-2 rounded-lg border-blue-500"
        type="text"
        name="Email"
        value=""
        id="Email"
      />
      <p>Details</p>
      <textarea
        name="Details"
        class="border-2 outline-none rounded-lg border-blue-500 h-40"
      ></textarea>
      <br>
      <button class="m-4 ml-0 px-8 py-1 font-semibold rounded-2xl border-2 border-white">Submit</button>
    </div>
  </div>
</template>
