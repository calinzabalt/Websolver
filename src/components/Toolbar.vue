 <template>
     <div>
   <v-navigation-drawer
      v-model="drawer"
      fixed
      app
    >
      <v-list>
        <v-list-tile to="/">
          <v-list-tile-action>
            <v-icon>home</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title>Home</v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
        <v-list-tile to="/work">
          <v-list-tile-action>
            <v-icon>work</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title>Services</v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
        <v-list-tile href="https://calinzabalt.github.io/CozmaCalin-Blog/" target="blank">
          <v-list-tile-action>
            <v-icon>school</v-icon>
          </v-list-tile-action>
           <v-list-tile-content>
            <v-list-tile-title>Blog</v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
        <v-list-tile to="/contact">
          <v-list-tile-action>
            <v-icon>email</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title>Contact</v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
        <v-list-tile to="/terms">
          <v-list-tile-action>
            <v-icon>copyright</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title>Terms & Conditions</v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
        <v-list-tile to="/terms">
          <v-list-tile-action>
            <v-icon>info</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title>Privacy Policy</v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
      </v-list>
    </v-navigation-drawer>
    <v-toolbar color="indigo" dark fixed app>
      <v-toolbar-side-icon @click.stop="drawer = !drawer" aria-label="drawer"></v-toolbar-side-icon>
      <v-list-tile to="/#" >
      <v-toolbar-title>WebSolver</v-toolbar-title>
      </v-list-tile>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn aria-label="Home" flat to="/#">Home</v-btn>
        <v-btn aria-label="Services" flat to="/work">Services</v-btn>
        <v-btn aria-label="Blog" flat href="https://calinzabalt.github.io/CozmaCalin-Blog/" target="blank">Blog</v-btn>
        <v-btn aria-label="Contact" flat to="/contact">Contact</v-btn>
      </v-toolbar-items>  
    </v-toolbar>

</div>
</template>   
<style scoped>

</style>

<script>
  export default {
    data: () => ({
      drawer: false
    }),
    props: {
      source: String
    }
  }
</script>


