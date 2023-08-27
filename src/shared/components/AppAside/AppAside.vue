<template>
  <div class="AppAside">Aside</div>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
@import '../../styles/mixin.scss';
.AppAside {
  @include layout();
  height: 75vh;
  width: 180px;
  display: flex;
  flex-direction: column;
  padding: 24px 16px;
}
</style>
