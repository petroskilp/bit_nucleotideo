<template>
  <header
    v-if="
      $slidev.themeConfigs.logoHeader && $slidev.nav.currentLayout === 'intro2'
    "
    class="absolute w-full px-4 py-2 top-0 h-10 z-10"
  >
    <img
      :src="$slidev.themeConfigs.logoHeader"
      class="w-40 h-40 object-contain"
    />
  </header>
</template>
