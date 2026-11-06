<template>
  <div id="app">
    <nav>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/">Random Quotes</RouterLink>
      <RouterLink to="/contact">Contact</RouterLink>
    </nav>

    <RouterView />
  </div>
</template>

<style>
nav {
  padding: 20px;
  text-align: center;
}

nav a {
  margin: 0 15px;
  text-decoration: none;
  color: #2c3e50;
}

nav a.router-link-active {
  font-weight: bold;
}

#app {
  font-family: Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>