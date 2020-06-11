<template>
  <div>
    <form class="idea-form">
      <div>
        <label class="form-label" for="title">Idea title</label>
        <input type="text" />
      </div>
      <div>
        <label class="form-label" for="title">Idea description</label>
        <textarea type="text" />
      </div>
    </form>
    <button>Submit</button>
  </div>
</template>

<script>
export default {
  name: "Form"
};
</script>

<style>
.idea-form {
  text-align: left;
  width: 20em;
  margin: 2em auto 1em auto;
}
.form-label {
  display: block;
  margin-top: 1em;
}
input,
textarea {
  width: 100%;
  outline: none;
  font-size: 1.5em;
  font-family: "Open Sans", sans-serif;
  padding: 0.5em;
}

button {
  padding: 1em;
  font-size: 1em;
  border-radius: 0;
  border: none;
  outline: none;
}
</style>
