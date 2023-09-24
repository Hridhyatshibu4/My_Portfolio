<template>
  
    <nav class="navbar">
    <ul class="no-bullets">
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/about-section">About</router-link></li>
          <li><router-link to="/education-section">Education</router-link></li>
          <li><router-link to="/experience-section">Experience</router-link></li>
          <li><router-link to="/skills-section">Skills</router-link></li>
          <li><router-link to="/volunteering-section">Volunteering</router-link></li>
          <li><router-link to="/certifications-section">Certifications</router-link></li>
          <li><router-link to="/contact-section">Contact</router-link></li>
    </ul>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
