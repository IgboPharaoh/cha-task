<template>
  <v-app>
    <v-main>
      <form-section/>
    </v-main>
  </v-app>
</template>

<script>
import FormSection from './components/FormSection.vue';

export default {
  name: 'App',

  components: {
    FormSection,
  },

  data: () =>
    FormSection ({
    //
  }),
};
</script>
