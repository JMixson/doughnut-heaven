<script setup lang="ts"></script>

<template>
  <nav role="navigation">
    <a href="#">DH</a>

    <ul>
      <li><a href="#love">Why the Love?</a></li>
      <li><a href="#types">Types</a></li>
      <li><a href="#facts">Fun Facts</a></li>
      <li><a href="#credits">Credits</a></li>
    </ul>
  </nav>
</template>

<style scoped lang="css">
nav {
  display: flex;
  justify-content: space-between;
  font-family: var(--special-font);
  padding: 20px var(--padding-sides);
  font-size: var(--md-font-size);
}

ul {
  display: flex;
  list-style: none;

  li {
    display: inline-block;
    margin-inline-start: 15px;
  }
}

a {
  &:link,
  &:visited {
    text-decoration: none;
    color: var(--color-black);
  }

  &:hover,
  &:active {
    text-decoration: underline;
  }
}
</style>
