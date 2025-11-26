<template>
  <p>{{ message }}</p>
  <button @click="changer">{{ message }}</button>
  <button @click="countDeMoi++">+{{ countDeMoi }}</button>
  <span>My input</span> <input v-model="model" />
</template>

<script>
const model = defineModel();
export default {
  data() {
    return {
      message: "Hello",
      countDeMoi: 0,
    };
  },

  methods: {
    changer() {
      this.message = "Message modifié !";
      console.log("dans la fonction changer", this.message);
    },
  },
};
</script>
