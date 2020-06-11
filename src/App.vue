<template>
  <div class="container-inner">
    <h1 class="title">My ideas</h1>
    <h2>Welcome to my ideas site!</h2>
    <Form />
  </div>
</template>

<script>
import Form from "./components/Form";
export default {
  components: {
    Form
  },
  name: "app",
  data() {
    return {
      items: []
    };
  }
};
</script>

<style>
.title {
  font-family: "Bellota", cursive;
  font-size: 5em;
}
body {
  font-family: "Open Sans", sans-serif;
  text-align: center;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container-inner {
  width: 50%;
  margin: 0 auto;
}
</style>
