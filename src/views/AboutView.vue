<script setup>
import {useFlash} from "@/composables/useFlash";
import { counter } from "@/stores/counterStore";
let { flash } = useFlash();
</script>

<template>
  <div>
    <p>
      <button @click="flash('Yay', 'It works on the about page!', 'info')">Click Me</button>
      About page. The current count is {{ counter.count }}
    </p>
  </div>
</template>

