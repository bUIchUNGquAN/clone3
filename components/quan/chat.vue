<template>
  <div class="lg:py-1 lg:px-8">
    <div class="border-b shadow-lg divide-y-4 divide-slate-400/25">
      <div class="py-2">
        <p class="text-white text-2xl">Chat</p>
      </div>
    </div>
    <div class="flex flex-col items-center w-full gap-y-4">
      <div class="flex items-center w-full"></div>
      <div class="flex items-center w-full">
        <div class="flex items-start w-full space-x-2 max-w-[300px]">
          <div class="relative select-none w-8 h-8 rounded-full">
            <img
              src="https://c4.wallpaperflare.com/wallpaper/865/301/276/anime-solo-leveling-sung-jin-woo-hd-wallpaper-preview.jpg"
              class="object-cover w-full h-full select-none rounded-full"
            />
          </div>
          <div class="text-left">
            <div class="flex justify-start items-center mb-1">
              <span
                class="inline-flex items-center font-medium rounded-md text-xs px-1.5 py-0.5 dark:bg-orange-400 dark:bg-opacity-10 text-white bg-opacity-10 capitalize mr-1"
                >Player 1</span
              >
              <UIcon name="i-bxs-circle" color="green" dynamic />
            </div>
            <p class="text-sm text-gray-800">5 daika</p>
            <p class="break-words text-sm">blalalalal</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>
