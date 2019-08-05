<template>
<v-container grid-list-xl text-xs-center>
 <v-layout row wrap>

<v-flex xs12 md6 sm6>
  <v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="800"
    >
      <v-img
        :aspect-ratio="16/9"
        src="/imagini/portofolio1.png"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal display-3 white--text"
            style="height: 100%;"
          >
            $200-$500
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
        <h3 class="display-1 font-weight-light orange--text mb-2"><strong>Presentation website</strong></h3>
        <div class="font-weight-light title mb-2">
          <ul>
            <li><strong>Responsive Design</strong></li>
            <li><strong>Fast and Reliable</strong></li>
            <li><strong>Easy to Use</strong></li>
            <li><strong>Custom Design</strong></li>
          </ul>
        </div>
      </v-card-text>
    </v-card>
  </v-hover>
  </v-flex>

  
  <v-flex xs12 md6 sm6>
  <v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="800"
    >
      <v-img
        :aspect-ratio="16/9"
        src="/imagini/blog.png"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal display-3 white--text"
            style="height: 100%;"
          >
            $400-$900
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
        <h3 class="display-1 font-weight-light orange--text mb-2"><strong>Blog</strong></h3>
        <div class="font-weight-light title mb-2">
          <ul>
          <li><strong>Custom Design</strong></li>
          <li><strong>Responsive Design</strong></li>
          <li><strong>Effective Navigation</strong></li>
          <li><strong>Fast and Reliable</strong></li>
          
          </ul>
          </div>
      </v-card-text>
    </v-card>
  </v-hover>
  </v-flex>


  <v-flex xs12 md6 sm6>
  <v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="800"
    >
      <v-img
        :aspect-ratio="16/9"
        src="/imagini/real-estate1.png"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal display-3 white--text"
            style="height: 100%;"
          >
            $500-$1500
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
        <h3 class="display-1 font-weight-light orange--text mb-2"><strong>Real-Estate website</strong></h3>
        <div class="font-weight-light title mb-2">
          <ul>
          <li><strong>Effective Navigation</strong></li>
          <li><strong>Responsive Design</strong></li>
          <li><strong>Custom Design</strong></li>
          <li><strong>Usable Forms</strong></li>
          <li><strong>Fast and Reliable</strong></li>
          <li><strong>Easy to Use</strong></li>
          <li><strong>SEO Optimization</strong></li>
          <li><strong>Clean Code</strong></li>
          </ul>
        </div>
      </v-card-text>
    </v-card>
  </v-hover>
  </v-flex>


  <v-flex xs12 md6 sm6>
  <v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="800"
    >
      <v-img
        :aspect-ratio="16/9"
        src="/imagini/store.png"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal display-3 white--text"
            style="height: 100%;"
          >
            $800-$2000
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
        
        <h3 class="display-1 font-weight-light orange--text mb-2"><strong>e-Commerce website</strong></h3>
        <div class="font-weight-light title mb-2">
          <ul>
          <strong><li>Responsive Design</li></strong>
          <strong><li>SEO Optimization</li></strong>
          <strong><li>Effective Navigation</li></strong>
          <strong><li>Good Error Handling</li></strong>
          <strong><li>Fast and Reliable</li></strong>
          <strong><li>Custom Design</li></strong>
          <strong><li>User Friendly</li></strong>
          <strong><li>Usable Forms</li></strong>
          <strong><li>Clean Code</li></strong>
          </ul>
        </div>
      </v-card-text>
    </v-card>
  </v-hover>
  </v-flex>
</v-layout>
</v-container>
</template>

<style>
.v-card {
  box-shadow: 1px 1px 5px 1px rgba(0, 0, 0, 0.5);
}
.v-card li{
  margin-bottom: 10px;
}
ul{
  list-style-type: disc;
}
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: .7;
  position: absolute;
  width: 100%;
}
</style>