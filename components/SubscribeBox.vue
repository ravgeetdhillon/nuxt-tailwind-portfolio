<template>
  <div class="w-1/2 mx-auto bg-gray-800 px-6 py-8 rounded shadow-md">
    <h2 class="do-h2 text-white">Subscribe to Newsletter</h2>
    <p class="do-p text-gray-500">
      I will send tips and tricks related to Jamstack technologies every Tuesday
      morning.
    </p>
    <input
      type="email"
      class="block bg-gray-900 w-full py-2 px-4 rounded mb-4"
      name="email"
      placeholder="Your Email"
    />
    <button
      type="submit"
      class="inline-block bg-blue-100 rounded-full px-4 py-1 font-semibold text-blue-900"
    >
      Subscribe
    </button>
  </div>
</template>

<style lang="postcss" scoped>
.btn-special {
  @apply inline-block bg-blue-100 rounded-full px-4 py-1 font-semibold text-blue-900;
  &:hover {
    @apply bg-blue-200;
    transition: all 0.1s ease-in-out;
  }
}
</style>
