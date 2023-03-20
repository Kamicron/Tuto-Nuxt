<template>
  <div>
    <h1>test</h1>
    <Article
    titre = "Tutoriel Nuxt.js"
    contenu = "Ceci est un article"
    />
  </div>
</template>

<script>
import Article from '~/components/Article';

export default {
  components: {
    Article
  }
}
</script>