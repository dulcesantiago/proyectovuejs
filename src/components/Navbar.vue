<template>
  <div
    class="w-full dark:bg-gray-800 bg-white h-14 flex items-center bg-white z-20 w-full justify-between sticky top-0 flex z-10"
  >
    <div class="h-full flex items-center w-14">
      <button
        @click="$emit('click')"
        class="w-full dark:text-white h-full focus:outline-none pl-5 sm:hidden"
      >
        <i class="bx bx-menu bx-sm"></i>
      </button>
    </div>
    <div class="flex items-center">
      <span class="text-xs mr-4 cursor-pointer dark:text-white"
        >L18730278@pinotepa.tecnm.mx</span
      >
      <div class="overflow-hidden rounded-full mr-5 h-11 w-11">
        <img
          class="w-full object-cover cursor-pointer"
          src="../assets/logoitp.png"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>