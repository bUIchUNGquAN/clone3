<template>
  <div
    class="fixed flex flex-col justify-end z-[55] end-0 right-0 top-0 bottom-auto w-full sm:w-96"
  ></div>
  <div class="relative h-full min-h-full bg-slate-500">
    <!-- header -->
    <div
      class="sticky top-0 z-50 bg-slate-800 dark:bg-transparent backdrop-blur-xl shadow-lg"
    >
      <QuanHead />
    </div>
    <!-- menu -->
    <div class="mx-auto px-4 sm:px-6 lg:px-8 max-w-7xl grid grid-cols-12 gap-0">
      <div
        class="bg-slate-600 shadow-full xl:col-span-2 md:cols-span-5 col-span-12 md:block hidden md:sticky md:overflow-y-auto py-4"
      >
        <div>
          <QuanMenu />
        </div>
      </div>
      <div class="xl:col-span-8 md:col-span-5 col-span-4 lg:pl-12 md:pl-8">
        <QuanMain />
      </div>
      <div
        class="bg-slate-600 shadow-full xl:col-span-2 md:cols-span-4 col-span-12 md:block hidden md:sticky md:overflow-y-auto py-4"
      >
        <div>
          <QuanChat />
        </div>
      </div>
    </div>
  </div>
</template>
