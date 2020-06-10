<template>
  <form class="idea-form">
    <div>
      <label class="form-label" for="title">Idea title</label
      ><input type="text" />
    </div>
    <div>
      <label class="form-label" for="title">Idea description</label
      ><textarea type="text" />
    </div>
  </form>
</template>

<script>
export default {};
</script>

<style>
.idea-form {
  text-align: left;
  width: 20em;
  margin: 0 auto;
}
.form-label {
  display: block;
}
input,
textarea {
  width: 100%;
  outline: none;
}
</style>
