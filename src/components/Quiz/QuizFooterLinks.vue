<template>
  <div>
    <h5>{{ state.name }}</h5>
    <button @click.prevent="state.name = 'A New Quiz Name'">Change Quiz Name</button>
    <ul>
      <li><a href="#">Get a Job</a></li>
      <li><a href="#">Contact Us</a></li>
    </ul>
  </div>
</template>

<script setup>
// import { inject } from "vue";
import { state } from "@/stores/quizStore"
// let quiz = inject('quiz');
</script>
