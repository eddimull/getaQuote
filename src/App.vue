<template>
  <div class="bg-indigo-500 h-screen flex items-center content-center justify-center">
    <div>
      <router-view />
    </div>
  </div>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  data: () => ({
    showMenu: false,
    showProfileMenu: false,
  }),
})
</script>
