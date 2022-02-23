<template>
<div class="max-w-4xl p-4 text-gray-800 bg-white rounded-lg drop-shadow-2xl">
  <div class="mb-2">
    <div class="h-3 text-4xl text-left text-gray-600">“</div>
    <p class="px-4 text-2xl text-center text-gray-600">
      {{data.body}} - <em>{{data.author}}</em>
    </p>
    <div class="h-3 text-4xl text-right text-gray-600">”</div>
  </div>
</div>
</template>

<script>
export default {
    props:['data']
}
</script>

<style>

</style>