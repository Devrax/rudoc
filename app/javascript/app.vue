<template>
  <div id="app">
    <div class="flex h-screen items-center justify-center w-full">
      <p class="animate-pulse font-bold text-4xl">{{ message }}</p>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Rudoc with Rails!"
    }
  }
}
</script>
