<template>
  <button
    ref="_ref"
    class="my-button"
    :class="{
      [`my-button--${type}`]: type,
      [`my-button--${size}`]: size,
      'is-plain': plain,
      'is-round': round,
      'is-circle': circle,
      'is-disabled': disabled || loading
    }"
    :disabled="disabled || loading"
  >
    <My-Icon icon="spinner" spin v-if="loading" />
    <My-Icon :icon="icon" v-if="icon" />
    <span v-if="$slots.default">
      <slot />
    </span>
  </button>
</template>

<script setup>
import { ref } from 'vue'
import propObj from './props'
defineProps(propObj)

const _ref = ref(null)

defineExpose({
  ref: _ref,
})
</script>

<style lang="scss" scoped></style>

