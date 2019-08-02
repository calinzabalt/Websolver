<template>
  <v-container grid-list-xl text-xs-center>
    <v-layout row wrap>
      <v-flex xs12 md4 sm4>
        <v-card>
        <v-img
          src="/imagini/What.png"
          aspect-ratio="1.2"
        ></v-img>

        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0"><strong>What I Do</strong></h3>
            <h4 class="subheading" >I build unique and professional websites for every kind of companies, start-ups and freelancers.</h4>
          </div>
        </v-card-title>

        <v-card-actions>
          <v-btn dark type='button' aria-label="Services" to="/work" id="top" class="mx-1" color="#039BE5"><strong>Services</strong></v-btn>
        </v-card-actions>
      </v-card>
        </v-flex>

      <v-flex xs12 md4 sm4>
        <v-card>
        <v-img
          src="/imagini/how3.png"
          aspect-ratio="1.2"
        ></v-img>

        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0"><strong>How I Do It</strong></h3> 
            <h4 class="subheading" >I use technologies like Wordpress, Drupal, React.js, Vue.js, Nuxt.js to accomplish customer needs.</h4>
          </div>
        </v-card-title>

        <v-card-actions>
          <v-btn dark type='button' aria-label="Services" id="top" to="/work" class="mx-1" color="#039BE5"><strong>Services</strong></v-btn>
        </v-card-actions>
      </v-card>
      </v-flex>

      <v-flex xs12 md4 sm4>
        <v-card>
        <v-img
          src="/imagini/why2.png"
          aspect-ratio="1.2"
        ></v-img>

        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0"><strong>Why I Do It</strong></h3>
            <h4 class="subheading" >I build websites because I like to help people solve their problems and accomplish their goals and dreams.</h4>
          </div>
        </v-card-title>

        <v-card-actions>
         <v-btn dark type='button' aria-label="Services" id="top" to="/work" class="mx-1" color="#039BE5"><strong>Services</strong></v-btn>
        </v-card-actions>
      </v-card>
        
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style scoped>

.layout{
    padding-bottom: 40px;
}

@media screen and (min-width: 1200px) {
    .container {
      width: 70%;
  }
}

.v-card, img{
   border-radius: 3px;
   box-shadow: 1px 1px 5px 1px rgba(0, 0, 0, 0.5);
   background-color: #e9ebee;
}


</style>
