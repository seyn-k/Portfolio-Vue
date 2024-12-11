<template>
  <div id="app">
    <nav class="navbar">
      <div class="container">
        <a class="brand">SENTHIL</a>
        <ul class="nav-links">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Skills</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>
    <div class="content">
      <h1>I'm Senthil aka Seyn</h1>
      <p>Welcome to my world</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style scoped>
/* Navbar Styles */
.navbar {
  font-family: "Lucida Console", "Courier New", monospace;
  background-color: #333;
  color: white;
  padding: 2rem;
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.nav-links {
  list-style: none;
  display: flex;
  gap: 2rem;
}
.nav-links a {
  text-decoration: none;
  color: white;
  transition: color 0.3s;
}
.nav-links a:hover {
  color: #00bcd4;
}
.brand {
  font-size: 1.5rem;
  font-weight: bold;
}

/* Content Styles */
.content {
  font-family: Arial, Helvetica, sans-serif;
  padding: 2rem;
  text-align: center;
}
</style>
