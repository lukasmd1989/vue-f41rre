<template>
  <div>
    <label for="channel">Select Channel:</label>
    <select v-model="selectedChannel" id="channel">
      <option value="Display">Display</option>
      <option value="Social Media">Social Media</option>
    </select>
  </div>
</template>

<script>
export default {
  data() {
    return {
      selectedChannel: '',
    };
  },
};
</script>
