<script setup>

</script>
<template>
      <footer>
        <div class="footer-container">
          <div class="contact-info">
            <div class="footer-title">Quick Access Pages</div>
          <div class="link-container"><RouterLink to="/" class="link">Home</RouterLink></div>
          <div class="link-container"><RouterLink to="/about" class="link">About</RouterLink></div>
          <div class="link-container"><RouterLink to="/contact" class="link">Contact Us</RouterLink></div>
          </div>
          <div class="social-media">
            <div class="footer-title">Follow Us</div>
            <div class="link-container"><a href="javascript:void(0)">Instagram</a></div>
            <div class="link-container"><a href="javascript:void(0)">X (Twitter)</a></div>
            <div class="link-container"><a href="javascript:void(0)">Facebook</a></div>
            <div class="link-container"><a href="javascript:void(0)">Telegram</a></div>
          </div>
        </div>
        <div class="copyright"><p>&copy; All right reserved for <a href="https://www.github.com/tiredb0y">tiredb0y GitHub</a></p></div>
      </footer>
</template>
<style scoped>
a {
  color: rgb(11, 221, 211);
  text-decoration: none;
  letter-spacing: .05rem;
}
a:active {
  color: darkcyan;
}
.link-container {
  margin-top: 6px;
}
.copyright {
  margin: 3px 0 0 0;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-size: .8rem;
  letter-spacing: .09rem;
  padding-left: 10px;
  margin-bottom: 10px;
}
.copyright>p {
  margin: 0;
}
footer {
  background-color: #333;
  color: #fff;
  padding: 10px 0 3px 0;
}

.footer-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}

.contact-info{
    margin-left: 10px;
    
}

.footer-title {
  font-size: 1.5rem;
  color: #f0f0f0;
}


</style>