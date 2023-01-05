<template>
  <header
    v-if="$slidev.nav.currentPage > 1"
    class="absolute top-0 right-0 p-2 text-xs">
    <SlideCurrentNo />
    /
    <SlidesTotal />
  </header>
</template>
