<template>
  <div><h1>This is a basic Vue app deployed on {{ value }}</h1></div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "Jekyo"
    };
  }
};
</script>
