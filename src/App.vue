<script setup lang="ts">
const email = "y87cgp@gmail.com";
const tgLink = "https://t.me/y87cgp";
</script>

<template>
  <main>
    <h1>About me</h1>

    <h2>Core skills</h2>
    <ul>
      <li>React</li>
      <li>TypeScript</li>
      <li>NodeJS</li>
      <li>PostgreSQL</li>
    </ul>

    <h2>Secondary Skills (used at work)</h2>
    <ul>
      <li>Tailwind CSS</li>
      <li>State Managers: Redux, Zustand</li>
      <li>Linux, System Administration</li>
      <li>Telegram Bots</li>
      <li>Vite</li>
    </ul>

    <h2>Other Skills</h2>
    <ul>
      <li>Crypto</li>
      <li>Svelte</li>
      <li>Vue</li>
      <li>Github Actions</li>
      <li>Github Pages</li>
    </ul>

    <h2>Obviously Used (section for HR's)</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>Git</li>
      <li>JavaScript</li>
    </ul>

    <h2>Education</h2>
    <ul>
      <li>Moscow State University (Computer Science)</li>
    </ul>

    <nav class="contacts">
      <p>
        Telegram: <a :href="tgLink" target="_blank">{{ tgLink }}</a>
      </p>
      <p>
        Email: <a :href="`mailto:${email}`">{{ email }}</a>
      </p>
    </nav>
  </main>
</template>

<style scoped lang="scss">
main {
  overflow: auto;
  max-width: 1000px;
  margin-inline: auto;
  height: 100vh;
  height: 100dvh;
  padding-inline: 10px;
  background: white;
}

.contacts {
  background: palegreen;
  padding: 10px;

  p {
    margin: 0;
  }
}

:global(:root) {
  font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;

  color-scheme: light dark;

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  body {
    background: grey;
  }
}
</style>
