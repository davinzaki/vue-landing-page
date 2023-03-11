<template>
  <div class="contact">
    <div class="mx-32 justify-center items-center">
      <div class="text-center">
        <h1 class="text-8xl font-bold">Contact us!</h1>
        <h3 class="text-6xl font-bold mt-44 mb-8">Contact form</h3>
      </div>
      <div class="flex justify-center">
        <form class="flex flex-col gap-4 mr-2">
          <input
            type="text"
            name="name"
            placeholder="name"
            class="border-2 border-black p-2 placeholder-black"
          />
          <input
            type="email"
            name="email"
            placeholder="email address"
            class="border-2 border-black p-2 placeholder-black"
          />
          <textarea
            name="message"
            cols="30"
            rows="10"
            placeholder="message"
            class="border-2 border-black p-2 placeholder-black"
          ></textarea>
        </form>
        <div class="w-1/4">
          <img src="../assets/img/emo.png" />
        </div>
      </div>
      <button
        class="ml-[17rem] mt-8 mb-[20rem] p-4 px-10 rounded-full bg-black shadow-lg text-white"
      >
        Send
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
