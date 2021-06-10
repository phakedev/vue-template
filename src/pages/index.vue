<template>
  <div class="h-screen">
    <div class="flex items-center justify-center h-full">
      <div>
        <welcome />
        <div class="mt-4 flex justify-center items-center">
          <color-scheme />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
  import Welcome from '~/components/welcome.vue'
  import ColorScheme from '~/components/common/color.scheme.vue'
</script>
