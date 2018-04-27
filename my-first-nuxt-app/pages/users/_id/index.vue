<template>
  <section class="container">
      <nuxt-link to="/users">Users</nuxt-link>
  </section>
</template>

<script>
export default {
    validate (data) {
        return /^\d+$/.test(data.params.id)
    }
}
</script>
