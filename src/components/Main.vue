<script>
import axios from "axios"

</script>

<template>
<h2>Enter your prompt</h2>

  <div class="mb-3">
    <label for="word1" class="form-label">Your guess</label>
    <input type="text" class="form-control" id="word1"
           :value="prompt"
           @input="event=> prompt = event.target.value"
    >
  </div>

  <button class="btn btn-success" @click="clickHandler">Submit</button>

</template>

<style scoped>

</style>
