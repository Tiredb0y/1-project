<script setup>

</script>
<template>
    <div>
    <body>
      <footer>
        <div class="footer-container">
          <div class="contact-info">
            <h3><RouterLink to="/contact" class="link">Contact Us</RouterLink></h3>
          <p><RouterLink to="/" class="link">Home</RouterLink></p>
          <p><RouterLink to="/about" class="link">About</RouterLink></p>
          
          </div>
          <div class="social-media">
            <h3>Follow Us</h3>
          </div>
        </div>
        <div class="copyright">
          <p>Hello world</p>
        </div>
      </footer>

    </body>


</div>
</template>
<style scoped>
.link{
  text-decoration: none;
  color: #fff;
}
*{
    display: flexbox;
}
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

.footer-container {
  display: flex;
  justify-content: space-between;
}

.contact-info{
    margin-left: 10px;
    
}
.social-media {
  display: flex;
  justify-content: center;
  margin-right: 48%;
}

h3 {
  color: #fff;
}

.copyright {
  margin-top: 20px;
  text-align: center;
}

</style>