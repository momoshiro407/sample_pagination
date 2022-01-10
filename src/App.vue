<template>
  <ListView />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import ListView from '@/components/ListView.vue';

export default defineComponent({
  name: 'App',
  components: { ListView }
});
</script>

<style>
</style>
