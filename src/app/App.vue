<template>
  <div class="ApollonApp">
    <AppHeader />
    <AppAside />
    <main>
      <router-view />
    </main>
  </div>
</template>

<script setup lang="ts">
import { AppHeader, AppAside } from '@/shared/components';
</script>

<style lang="scss">
@import './global.scss';
@import '../shared/styles/mixin.scss';

.ApollonApp {
  transition: all 0.2s;
  background-image: url(../shared/assets/bg-1.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;
  display: flex;
  flex-wrap: wrap;
  padding: 20px;
  gap: 2%;
  main {
    @include layout();
    height: 75vh;
    width: calc(100% - 180px - 2%);
  }
}
</style>
