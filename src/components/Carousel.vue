<template>
    <v-container>
        <v-carousel :show-arrows="false" hide-delimiters>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      cover
    ></v-carousel-item>
  </v-carousel>
    </v-container>
  </template>
  
  <script>
    export default {
    data () {
      return {
        items: [
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg',
            title : "Bild1"
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
            title : "Bild2",
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
            title : "Bild3",
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
            title : "Bild4",
          },
        ],
      }
    },
  }
  </script>
  