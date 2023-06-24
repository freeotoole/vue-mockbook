<script setup lang="ts">
import VueMockbook from '../lib/VueMockbook.vue'
</script>

<template>
  <div class="container">
    <h1 class="text-xl mt-8">
      CSS only mockup of a MacBook Pro for displaying screenshots
    </h1>
    <p>
      A few years ago I was working on my portfolio and looking for a macbook
      image to PhotoShop screenshots into. I found this
      <a href="https://css-tricks.com/forums/topic/pure-css-macbook-pro/"
        >Pure CSS Macbook Pro</a
      >
      post on the old css-tricks forum teasing where a user put a screenshot of
      said pure css macbook but no actual code. Looking at the image I realised
      there probably wasn't much to it, so got to using all the css gradients to
      recreate the macbook.
    </p>
    <VueMockbook screen-shot="screenshot-freeotoole.png" url="freeotoole.com" />
    <p>
      I've used this a few times since, and it's been a fun little project to
      work on. I've added a few more features since then, like the the url bar,
      complete with dark mode toggle as well as making in accessible to keyboard
      users.
    </p>
  </div>
</template>

<style>
.container {
  display: flex;
  flex-direction: column;
  max-width: 90rem;
  justify-content: stretch;
  margin: 0 auto;
  position: relative;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
