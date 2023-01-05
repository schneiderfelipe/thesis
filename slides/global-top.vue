<template>
  <header
    v-if="1 < $slidev.nav.currentPage && $slidev.nav.currentPage < $slidev.nav.total"
    class="absolute top-6px right-10px text-xs">
    <SlideCurrentNo />
    /
    <SlidesTotal />
  </header>
</template>
