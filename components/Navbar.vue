<template>
  <div
    class="px-24 w-full flex items-center justify-between bg-gray-600 text-white"
  >
    <h1 class="font-bold text-2xl my-auto">David Ratier</h1>
    <ul class="flex items-center">
      <li>
        <a class="text-white hover:text-yellow no-underline" href="#">Home</a>
      </li>
      <li>
        <a class="text-white hover:text-yellow no-underline" href="#">Resume</a>
      </li>
      <li>
        <a class="text-white hover:text-yellow no-underline" href="#"
          >Projects</a
        >
      </li>
      <li>
        <a class="text-white hover:text-yellow no-underline" href="#">Blog</a>
      </li>
    </ul>
  </div>
</template>

<style scoped>
ul,
li {
  @apply m-0 p-0;
}

li > a {
  @apply inline-block py-6 px-8 my-0;
}

li::before {
  @apply hidden;
}
</style>
