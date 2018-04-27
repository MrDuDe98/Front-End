<template>
  <app-quote>
      <h2>{{posuto}}</h2>
      <p>{{valor}}</p>
  </app-quote>
</template>
<script>
import appQuote from "@/components/app-quote";

export default {
  components: {
      appQuote
  },
  porps:{
      produto: {
          type: String,
          required: true
      },
      valor: {
          type: Number,
          required: true
      }
  }
}
</script>

