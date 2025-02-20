<template>
  <div class="main-layout">
    <Header>ok</Header>
    <main>
      <slot></slot>
    </main>
    <Footer />
  </div>
</template>

<script setup>
import Header from './Partial/Header.vue';
</script>