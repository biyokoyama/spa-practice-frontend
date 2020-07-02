<template>
  <a :href="href">
    Googleアカウントでログインする
  </a>
</template>

<script>
export default {
  computed: {
    href () {
      return `${process.env.SPA_PRACTICE_BACKEND_BASE_URL}/users/auth/google_oauth2`
    }
  }
}
</script>
