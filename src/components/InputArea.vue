<template>
    <v-row>
        <v-col cols="10" style="padding: 3;">
            <textarea v-model="message" placeholder="edit me" style="width: 100%;" />
        </v-col>
        <v-col cols="2" style="padding: 3;">
            <v-btn large color="purple" >
                ADD
            </v-btn>
        </v-col>
    </v-row>
</template>

<script>
export default {
  name: 'InputArea',

  data: () => ({
    message: '',
  }),
}
</script>
