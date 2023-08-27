<template>
  <div class="AppHeader">Header</div>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
@import '../../styles/mixin.scss';
.AppHeader {
  @include layout();
  height: 100px;
  padding: 10px 40px;
  width: 100%;
  display: flex;
  align-items: center;
  color: var(--color-white);
}
</style>
