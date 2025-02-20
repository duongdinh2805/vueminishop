<template>
  <div class="main-layout">
    <Header />
    <main>
      <slot></slot>
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from './Partial/Header.vue';
</script>