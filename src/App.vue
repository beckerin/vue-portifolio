<script>
export default {
  data() {
    return {
      a: "Botão",
    };
  },
  methods: {
    changeTo(val) {
      this.a = val;
    },
  },
};
</script>

<template>
  <div id="app">
    <div>
      <b-button @click="changeTo('Baton')">{{ a }}</b-button>
    </div>
  </div>
</template>
