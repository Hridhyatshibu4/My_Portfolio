<!-- NavBar.vue -->
<template>
  <nav class="navbar">
    <ul>
          <li><router-link to="/">Home</router-link></li>          
          <li><router-link to="/about-section">AboutSection</router-link></li>
          <li><router-link to="/education-section">EducationSection</router-link></li>
          <li><router-link to="/experience-section">ExperienceSection</router-link></li>
          <li><router-link to="/skills-section">SkillsSection</router-link></li>
          <li><router-link to="/volunteering-section">VolunteeringSection</router-link></li>
          <li><router-link to="/certifications-section">CertificationsSection</router-link></li>
          <li><router-link to="/contact-section">ConatctSection</router-link></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped>
/* Add your CSS styles for the navigation bar here */
</style>
