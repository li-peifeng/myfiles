<template>
  <div>
{{ storageConfigStore.globalConfig?.icp }}
  </div>
</template>

<script setup>
import useStorageConfigStore from "~/stores/storage-config";
let storageConfigStore = useStorageConfigStore();
</script>

<style scoped>

</style>
