<template>
  <div class="container mx-auto h-screen">
    <h1 class="text-6xl text-gray-500 my-2">Grid Layout</h1>
    <div class="grid grid-cols-5 gap-2 grid-rows-5 bg-gray-50 p-2">
      <div
        class="
          h-20
          bg-red-200
          col-start-1 col-span-2
          row-start-1 row-span-2
          flex
          items-center
          justify-center
        "
      >
        <span class="text-4xl text-white select-none">1</span>
      </div>
      <div
        class="
          h-20
          bg-blue-200
          col-start-2 col-span-2
          row-start-2 row-span-2
          flex
          items-center
          justify-center
          order-1
          opacity-50
        "
      >
        <span class="text-4xl text-white select-none">2</span>
      </div>
      <div
        class="
          h-20
          bg-green-200
          col-start-3 col-span-3
          row-start-3 row-span-3
          flex
          items-center
          justify-center
        "
      >
        <span class="text-4xl text-white select-none">3</span>
      </div>
    </div>
  </div>
</template>
