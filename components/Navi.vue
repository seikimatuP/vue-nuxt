<template>
  <nav>
    <nuxt-link to="/">TOP</nuxt-link>
    <nuxt-link to="/dog">Dog</nuxt-link>
    <nuxt-link to="/cat">Cat</nuxt-link>
  </nav>
</template>

<style scoped>
/* ナビゲーション */
nav {
  display: flex;
  align-items: center;
  background: #222;
}
nav a {
  display: block;
  padding: 0.5em;
  color: #eee;
  line-height: 1em;
  text-decoration: none;
}
/* アクティブなリンク */
.nuxt-link-exact-active {
  background: #64c9a2;
}
</style>