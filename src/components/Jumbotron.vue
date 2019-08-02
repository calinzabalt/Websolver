<template>
  <v-jumbotron height="100%" :gradient="gradient" dark>
    <v-container fill-height>
      <v-layout align-center>
        <v-flex>
          <h3 class="display-3">About me!</h3>
   <v-avatar size="120" margin="">
      <img
        src="/imagini/me.png"
        alt="MasterCalin"
      >
    </v-avatar>
          <span class="subheading"><p>My name is Cozma Viorel Calin, I'm a professional web developer and a becoming entrepreneur.
By building websites and solving problems, I developed a purpose that give me energy and keep me motivated for accomplishing every task in a very short time with a high quality.</p></span>

          <v-divider class="my-3"></v-divider>
          <v-btn type='button' to="/contact" id="top"
            aria-label="contact"
            class="mx-0"  
            color="#039BE5"
            large
          >
            Contact
          </v-btn>
        </v-flex>
      </v-layout>
    </v-container>
  </v-jumbotron>
</template>

<style scoped>
   
  p{
    font-size: 23px;
    font-family: "eurostile",sans-serif;
    font-weight: 300;
  }

.v-avatar {
  padding: 0;
  margin-bottom: 10px;
}

.v-jumbotron p {
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

</style>

<script>
  export default {
    data: () => ({
      gradient: 'to top, #00796B, #3F51B5'
    })
  }
</script>