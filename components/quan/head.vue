<template>
  <div
    class="mx-auto px-4 content-center sm:px-6 lg:px-8 max-w-7xl flex items-center h-[50px]"
  >
    <div class="flex items-center md:hidden mr-2">
      <span class="w-7 h-7 cursor-pointer">
        <UIcon name="i-bx-menu-alt-left" color="white" dynamic />
      </span>
    </div>
    <div class="flex flex-rows items-center mr-auto gap-40">
      <a href="#">
        <div class="flex items-center list-none">
          <p class="text-2xl text-white text-center font-bold uppercase">
            game
            <span class="text-2xl text-red-600 text-center font-bold uppercase"
              >arena</span
            >
          </p>
        </div>
      </a>
      <div class="flex items-center gap-5">
        <UInput
          icon="i-heroicons-magnifying-glass-20-solid"
          size="sm"
          color="red"
          trailing
          placeholder="Search..."
        />
        <UButton color="red">Search</UButton>
      </div>
    </div>
    <div class="flex justify-end items-center gap-4">
      <div class="flex items-center ml-1 gap-1">
        <p class="text-sm text-white text-center">600k VND</p>
        <UIcon name="i-bxs-circle" color="yellow" dynamic />
      </div>
      <div class="flex items-center ml-1">
        <UButton type="button" size="xm" variant="ghost">
          <span class="flex-shrink-0">
            <UIcon name="i-bxs-wallet" dynamic />
          </span>
        </UButton>
      </div>
      <div class="flex items-center ml-1">
        <UButton type="button" size="xm" variant="ghost">
          <span class="flex-shrink-0">
            <UIcon name="i-bxs-chat" dynamic />
          </span>
        </UButton>
      </div>
      <div class="flex items-center ml-1">
        <UButton type="button" size="xm" variant="ghost">
          <span class="flex-shrink-0">
            <UIcon name="i-bxs-bell" dynamic />
          </span>
        </UButton>
      </div>
      <div class="flex items-center ml-1">
        <UButton type="button" variant="ghost"> Dang Nhap </UButton>
      </div>
    </div>
  </div>
</template>
