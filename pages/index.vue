<script setup lang="ts">
useHead({
    titleTemplate: 'Hydrium',
})
</script>

<template>
  <Nav/>
  <header>
    <div class='logo'>
        <span>
          <h1 class=''>Hydrium</h1>
        </span>
        <nav>
          <NuxtLink to="/">INÍCIO</NuxtLink>
          <NuxtLink to="/projetos/ativos">PROJETOS</NuxtLink>
          <NuxtLink to="/sobre">SOBRE</NuxtLink>
        </nav>
    </div>
  </header>
  <TheWelcome/>
</template>

<style scoped>
.logo{
margin: 0 auto;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: var(--color-text);
}

h1{
padding: 0 48px;
    width: 100%;
    font-size: 5rem;
}

h3{
  color: var(--color-text);
  margin-top: -1rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin: 2rem 0 ;
}

nav a {
  color: var(--color-text);
  font-weight: bold;
  font-size: .9rem;
}
nav a:hover {
  background-color: #85ebd954;
}

nav a.router-link-exact-active {
  color: #85ebd9;
}

nav a.router-link-exact-active:hover {
  color: var(--color-text);
  color: #85ebd9;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}
</style>
