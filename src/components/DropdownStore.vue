<template>
  <div>
    <label for="store">Select Store(s):</label>
    <select multiple v-model="selectedStores" id="store">
      <option v-for="store in stores" :key="store">{{ store }}</option>
    </select>
  </div>
</template>

<script>
export default {
  data() {
    return {
      stores: ['Store A', 'Store B', 'Store C', /* Add more stores */],
      selectedStores: [],
    };
  },
};
</script>
