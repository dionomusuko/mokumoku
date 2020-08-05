<template>
  <main>
    <about />
    <skills />
    <experiences />
    <blogs />
  </main>
</template>

<script>
import About from '@/pages/about'
import Experiences from '@/pages/experiences'
import Skills from '@/pages/skills'
import Blogs from '@/pages/blogs'

export default {
  components: {
    About,
    Experiences,
    Skills,
    Blogs
  }
}
</script>

<style></style>
