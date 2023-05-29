<script setup lang='ts'>
import { UserAvatar } from '@/components/common'

// const Setting = defineAsyncComponent(() => import('@/components/common/Setting/index.vue'))

// const show = ref(false)
</script>

<template>
  <header class="flex items-center justify-between min-w-0 p-4 overflow-hidden border-b dark:border-neutral-800 my-3">
    <div class="flex-1 flex-shrink-0 overflow-hidden">
      <UserAvatar />
    </div>
  </header>
</template>
