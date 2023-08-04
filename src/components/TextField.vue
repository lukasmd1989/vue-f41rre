<template>
  <div>
    <label :for="label">{{ label }}:</label>
    <input v-model="value" :type="type" :id="label" />
  </div>
</template>

<script>
export default {
  props: {
    label: String,
    type: {
      type: String,
      default: 'text',
    },
    value: String,
  },
};
</script>
