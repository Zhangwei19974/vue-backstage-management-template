<template>
  <div>
    appProvider
    {{ name }}

    <slot></slot>
  </div>
</template>

<script lang="ts" setup name="AppProvider">
withDefaults(defineProps<{ name: string }>(), {
  name: 'test',
});
</script>

<style lang="less" scoped></style>
