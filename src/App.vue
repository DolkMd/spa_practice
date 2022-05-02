<template>
  <v-app>
    <v-main>
      <InputArea />
    </v-main>
  </v-app>
</template>

<script>
import InputArea from './components/InputArea.vue'

export default {
  name: 'App',

  components: {
    InputArea,
  },

  data: () => ({
    //
  }),
}
</script>
