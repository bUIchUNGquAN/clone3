<template>
  <div class="p-2 bg-white">
    <div class="realtive space-y-2">
      <UTabs :items="tabs" />
    </div>
    <div class="relative p-2"></div>
    <div class="p-2 bg-white">
      <div class="px-4 py-5">
        <QuanLoginForm />

        <QuanRegisterForm />
      </div>
    </div>
  </div>
</template>
<script setup>
const currentTab = ref("login");

const tabs = [
  { label: "Dang nhap", value: "login" },
  { label: "Dang ky", value: "register" },
  { label: "Quen mat khau", value: "forgot" },
];
</script>
