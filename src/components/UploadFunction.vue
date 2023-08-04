<template>
  <div>
    <input type="file" @change="handleFileChange" />
  </div>
</template>

<script>
export default {
  methods: {
    handleFileChange(event) {
      const file = event.target.files[0];
      // Handle the file upload logic here.
    },
  },
};
</script>
