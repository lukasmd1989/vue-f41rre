<template>
  <div>
    <dropdown-store />
    <dropdown-channel />
    <text-field label="Text 1" v-model="text1" />
    <text-field label="Text 2" v-model="text2" />
    <date-selector label="Start Date" v-model="startDate" />
    <date-selector label="End Date" v-model="endDate" />
    <upload-function />
  </div>
</template>

<script>
import DropdownStore from './components/DropdownStore.vue';
import DropdownChannel from './components/DropdownChannel.vue';
import TextField from './components/TextField.vue';
import DateSelector from './components/DateSelector.vue';
import UploadFunction from './components/UploadFunction.vue';

export default {
  components: {
    DropdownStore,
    DropdownChannel,
    TextField,
    DateSelector,
    UploadFunction,
  },
  data() {
    return {
      text1: '',
      text2: '',
      startDate: '',
      endDate: '',
    };
  },
};
</script>
