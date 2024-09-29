<template>
  <div class="m-10">
    <Alert type="info" :text="alert" />
    <Alert type="success" :text="alert" class="mt-4" closable />
    <Alert type="warning" :text="alert" class="mt-4" />
    <Alert type="error" :text="alert" class="mt-4" closable />
    <Alert :text="alert" class="mt-4" closable />
  </div>
</template>

<script setup>
const alert = ref("Simple information text.");
</script>
