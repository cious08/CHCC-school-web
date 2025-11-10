<template>
  <footer class="footer">
    <p>
    <a href="https://github.com/cious08/CHCC-school-web.git" target="_blank">
      Visit The Website of Concepcion Holy Cross College Inc.
    </a>
  </p>

    <!-- Footer Title -->
    <!-- Bottom Copyright -->
    <div class="footer-bottom">
      <br></br>
      <p>
        &copy; {{ new Date().getFullYear() }} Concepcion Holy Cross College Inc.. All rights reserved.
        | info@chcc.edu.ph | (045) 923 0747
      </p>
    </div>

    <!-- Social Icons -->
    <div class="footer-socials">
      
      
    </div>
  </footer>
</template>

<script setup>
</script>

<style>
.footer {
  background: #0a2c82;
  padding: 2rem 0rem 0;
  color: #000;
}

.footer-title {
  text-align: center;
  margin-bottom: 2rem;
}

.footer-title h2 {
  font-size: 1.8rem;
  color: #0a2c82; /* deep blue */
  font-weight: bold;
}
.footer-bottom {
  background: #0a2c82;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
  font-size: 0.9rem;
}

.footer-socials {
  background: #0a2c82;
  text-align: center;
  padding: 1rem 0;
}

.footer-socials a {
  color: white;
  margin: 0 0.5rem;
  font-size: 1.3rem;
  transition: color 0.2s;
}

.footer-socials a:hover {
  color: #ffd700; /* gold hover effect */
}
</style>
