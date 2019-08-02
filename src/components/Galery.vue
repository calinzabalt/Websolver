<template>
<div>
  <v-container grid-list-sm>
    <div class="images">
    <v-layout row wrap>
     <v-flex xs12 md6>
        <v-img src="/imagini/web-design/0071.webp" aspect-ratio="1.7"></v-img>
    </v-flex>
  
      <v-flex xs12 md6>
        <v-img src="/imagini/web-design/0073.webp" aspect-ratio="1.7"></v-img>
      </v-flex>


      <v-flex xs12 md6>
         <v-img src="/imagini/web-design/grass.webp" aspect-ratio="1.7"></v-img>
      </v-flex>

     <v-flex xs12 md6>
        <v-img src="/imagini/web-design/league of zabalt.webp" aspect-ratio="1.7"></v-img>
     </v-flex>

      <v-flex xs12 md6>
        <v-img src="/imagini/web-design/remastered zabalt.webp" aspect-ratio="1.7"></v-img>
     </v-flex>

      <v-flex xs12 md6>
        <v-img src="/imagini/web-design/planeta.webp" aspect-ratio="1.7"></v-img>
     </v-flex>   

    </v-layout>
    </div>
  </v-container>

<v-container fluid>
<v-layout row wrap>
<v-flex>
<iframe title="videos" src="https://www.youtube.com/embed/olyZHJrjrh8" frameBorder="0" allowFullScreen></iframe>
</v-flex>

<v-flex >
<iframe title="videos" src="https://www.youtube.com/embed/1qNz8LDjG_I" frameBorder="0" allowFullScreen></iframe>
</v-flex>

<v-flex>
<iframe title="videos" src="https://www.youtube.com/embed/srrh_u1nMG0" frameBorder="0" allowFullScreen></iframe>
</v-flex>


<v-flex>
<iframe title="videos" src="https://www.youtube.com/embed/XZppMeWxCuk" frameBorder="0" allowFullScreen></iframe>
</v-flex>
</v-layout>
</v-container>

</div>
</template>

<style scoped>

.images{
  background-color: white;
}

iframe{
  width: 500px;
  height: 300px;
}

@media screen and (max-width:610px) {
  iframe{
    width: 340px;
    height: 240px;
  }
}

@media screen and (max-width:430px) {
  iframe{
    width: 240px;
    height: 180px;
  }
}

iframe{
  padding-bottom: 20px;
}

</style>

