<template>
  <main className="px-6 h-screen flex items-center justify-center">
    <div className="text-center">
      <h1 className="text-3xl font-medium">Welcome to Vue.js!</h1>
      <p className="text-zinc-500 mt-1">Vue.js starter template!</p>

      <div>
        <div className="my-4">
          <a
            href="https://github.com/phakedev/vue-template"
            target="_blank"
            rel="noopener noreferrer"
            title="Github"
            className="inline-flex items-center gap-2 border-transparent"
          >
            phakedev/vue-template
          </a>
        </div>

        <color-scheme />
      </div>
    </div>
  </main>
</template>

<script lang="ts" setup>
  // vue sfc style
  import Welcome from '@/components/welcome.vue'
  import ColorScheme from '@/components/common/ColorScheme.vue'
</script>
