<template>
  <UForm class="space-y-4">
    <UFormGroup label="User" name="user">
      <UInput placeholder="nhap tai khoan ....." icon="i-heroicons-user">
      </UInput>
    </UFormGroup>
    <UFormGroup label="Password" name="password">
      <UInput
        type="password"
        placeholder="nhap mat khau ....."
        icon="i-heroicons-material-symbols:lock-outline"
      />
    </UFormGroup>

    <UButton type="submit"> dang nhap </UButton>
  </UForm>
</template>

<script setup></script>
