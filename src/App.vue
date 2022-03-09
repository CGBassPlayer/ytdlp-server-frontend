<template>
  <div id="app" class="bg-white dark:bg-gray-800">
    <Theme/>
    <search/>
  </div>
</template>

<script>

import Search from "@/components/Search";
import Theme from "@/components/Theme";

export default {
  name: 'App',
  components: {
    Theme,
    search: Search,
  },
}
</script>

<style>

</style>
