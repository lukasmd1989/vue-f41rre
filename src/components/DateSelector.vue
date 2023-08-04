<template>
  <div>
    <label :for="label">{{ label }}:</label>
    <input v-model="selectedDate" type="date" :id="label" />
  </div>
</template>

<script>
export default {
  props: {
    label: String,
    selectedDate: String,
  },
};
</script>
