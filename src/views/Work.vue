<template>
<v-container fluid style="margin: 0px; padding: 0px; width: 100%">
  <div class="work">
    <div id="top"><h1>Services</h1></div>
    <p>From hosting and finding the right domain, to deployment and maintenance the website daily.</p>
      <Servcards />
        <div id="top1"><h1>Here you find some examples of my latest projects</h1></div>
        
            <LazyHydrate when-visible>
            <Carousel />
            </LazyHydrate>

            <LazyHydrate when-visible>
            <Table slot-scope="{ hydrated }"
              v-if="hydrated"/>
            </LazyHydrate>
  </div>
</v-container>
</template>

<script>
import LazyHydrate from 'vue-lazy-hydration';

export default {
  name: 'services',
  metaInfo: {
    title: 'Services',
  meta: [
    {name: 'description', content:'Welcome!- Here you will find my latest projects that I built along the time'}
  ] 
  },
  components: {
   LazyHydrate,
    Carousel: () => import('../components/Carousel.vue'),
    Table: () => import('../components/Table.vue'),
    Servcards: () => import('../components/Servcards.vue'),
  }
}
</script>

<style scoped>
.work{
  background-color: #e9ebee
}
.work h1{
  color: #293347;
}

.work p{
  padding-bottom: 10px;
  color: #293347;
  margin: 10px;
  font-size: 22px;
  font-family: "eurostile",sans-serif;
  font-weight: 300;
}

#top h1{
  padding-top: 30px;
}

#top h1{
  font-size: 40px;
}

#top1 {
  margin: 20px;
}

</style>


