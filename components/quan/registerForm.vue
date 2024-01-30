<template>
  <UForm class="space-y-4">
    <UFormGroup label="Tai khoan" name="user">
      <UInput placeholder="....." icon="i-bxs-user"> </UInput>
    </UFormGroup>
    <UFormGroup label="Email" name="Email">
      <UInput
        placeholder=" ....."
        icon="i-heroicons-magnifying-glass-20-solid"
      />
    </UFormGroup>
    <UFormGroup label="Dien thoai" name="phone">
      <UInput
        placeholder=" ....."
        icon="i-heroicons-magnifying-glass-20-solid"
      />
    </UFormGroup>
    <UFormGroup label="Password" name="password">
      <UInput
        type="password"
        placeholder=" ....."
        icon="i-heroicons-magnifying-glass-20-solid"
      />
    </UFormGroup>
    <UFormGroup label="Ma moi" name="Ma moi">
      <UInput
        placeholder="Nhap ma moi neu co"
        icon="i-heroicons-magnifying-glass-20-solid"
      />
    </UFormGroup>

    <UButton type="submit"> dang ky </UButton>
  </UForm>
</template>

<script setup></script>
