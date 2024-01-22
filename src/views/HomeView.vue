<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import { ref } from "vue"

let message = ref("Hello world!")

// setTimeout(() => {
// 	message.value = "I have been Changed!"
// }, 2000);
let doSomething = () => {
	alert("doing it now...")
}
</script>

<template>
  <main>
    <!-- <TheWelcome /> -->
    <p>
      {{ message }}
    </p>
    <p>
      <!-- <input type="text" v-model="message"> -->
	  <button @click="doSomething">Click Me</button>
    </p>
  </main>
</template>
