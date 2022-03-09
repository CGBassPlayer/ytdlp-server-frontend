<template>
  <div class="flex flex-col justify-center items-center h-screen">
    <h1 class="text-4xl text-gray-900 dark:text-gray-100 mb-6">YT-DLP Server</h1>
    <form>
      <label class="text-gray-900 dark:text-gray-100">Enter URL</label>
      <input class="bg-gray-300 dark:bg-gray-600 w-full" placeholder="https://www.youtube.com/watch?v=ouncVBiye_M"/>
      <button type="submit" class="bg-red-800 w-full mt-4 text-gray-100">Search</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "Search",
  data: function () {
    return {}
  }
}
</script>

<style scoped>

</style>