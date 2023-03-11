<template>
  <div
    class="navbar flex black text-black shadow-md justify-between border items-center m-8 mx-32 mb-16 p-4 px-14 rounded-full"
  >
    <h3 class="text-[45px] font-bold text-[#EE7C54]">LOGO</h3>
    <div class="navbar-list flex w-1/2 justify-evenly text-[24px]">
      <router-link to="/" class="focus:underline focus:underline-offset-8"
        >Home</router-link
      >
      <router-link to="/about" class="focus:underline focus:underline-offset-8"
        >About</router-link
      >
      <router-link
        to="/contact"
        class="focus:underline focus:underline-offset-8"
        >Contact</router-link
      >
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
