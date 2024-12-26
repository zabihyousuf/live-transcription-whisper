<template>
  <div class="flex flex-col h-screen">
    <main class="flex-1 bg-gray-100 p-4 overflow-auto">
      <slot></slot>
    </main>
  </div>
</template>

<style>
html, body, #__nuxt {
  height: 100%;
}
</style>