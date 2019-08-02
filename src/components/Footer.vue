<template>
  <v-footer dark height="100%" color="teal">
    <v-layout justify-center row wrap>
    <v-flex xs12 sm4>
      <div class="social">
        <p>Social media links:</p>
        <v-btn aria-label="linkedn" type='button' href="https://www.linkedin.com/in/cozma-viorel-calin-947658145/" target="blank" large icon class="light-blue darken-3">
            <v-icon medium>fa-linkedin</v-icon>
        </v-btn>
        <v-btn aria-label="facebook" type='button' href="https://www.facebook.com/CozmaViorelCalinPFA/?modal=admin_todo_tour" target="blank" large icon class="light-blue darken-4">
             <v-icon medium>fa-facebook</v-icon>
        </v-btn>
        <v-btn aria-label="youtube" type='button' href="https://www.youtube.com/channel/UC2CNVDGd1odpr7UqsiIM68g?view_as=subscriber" target="blank" large icon class="deep-orange darken-4">
            <v-icon medium>fa-youtube</v-icon>
        </v-btn>
         <v-btn aria-label="instagram" type='button' href="https://www.instagram.com/cozmaviorelcalin/" target="blank" large icon class="orange darken-3">
            <v-icon medium>fa-instagram</v-icon>
        </v-btn>
        <v-btn aria-label="instagram" type='button' href="https://twitter.com/Cozmaviorelcal1" target="blank" large icon class="light-blue darken-2">
            <v-icon medium>fa-twitter</v-icon>
        </v-btn>
      </div>
    </v-flex> 

    <v-flex xs12 sm4>
      <div class="available">
      <p>Cozma Viorel Calin (PFA)</p>
      <p>Email: websolvercalin@gmail.com</p>
      <p>Phone: 0740 691 940</p>
       <v-btn aria-label="contact" type='button' to="/contact" id="v-parallax" color="blue" large><strong>Message me</strong></v-btn> 
        
    </div>
    </v-flex> 

    <v-flex xs12 sm4>
      <div class="links">
        <p>Useful links:</p>
         <v-btn aria-label="terms" flat to="/terms"><h3>Terms & Conditions</h3></v-btn><br/>
         <v-btn aria-label="privacy" flat to="/terms"><h3>Privacy Policy</h3></v-btn>
        </div>
    </v-flex>  
    <div class="copy">
   <h3>&copy;2019 — <strong>All rights reserved</strong></h3>
    </div>
    </v-layout>
    <cookie-law theme="blood-orange--rounded"/>
  </v-footer>
</template>

<script>
import CookieLaw from 'vue-cookie-law'
  export default {
    components: { CookieLaw }
  }
</script>

<style scoped>

.v-footer p{
  font-size: 20px;
  margin: 0;
  padding: 0;
  font-weight: 400;
}

.copy{
  margin-bottom: 10px;
}

.social{
  margin-top: 10px;
  padding: 20px;
}

.links{
  margin-top: 10px;
  padding: 20px;
}

.available{
  padding: 20px;
}
 
</style>
