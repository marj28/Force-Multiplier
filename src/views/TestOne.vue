<template>
  <v-card
    class="mx-auto"
    max-width="100%"
  >
      <v-row dense>
        <v-col
          v-for="card in cards"
          :key="card.title"
          :cols="card.flex"
        >
          <v-card>
            <v-img
              :src="card.src"
              class="align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="100%"
              cover
            >
              <v-card-title class="text-white" v-text="card.title"></v-card-title>
              <h1>honey</h1>
            </v-img>

            <v-card-actions>
              <v-spacer></v-spacer>

              <v-btn size="small" color="surface-variant" variant="text" icon="mdi-heart"></v-btn>

              <v-btn size="small" color="surface-variant" variant="text" icon="mdi-bookmark"></v-btn>

              <v-btn size="small" color="surface-variant" variant="text" icon="mdi-share-variant"></v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
  </v-card>
</template>
<script>
  export default {
    data: () => ({
      cards: [
        { title: 'Favorite road trips', src: '@/assets/image.png', flex: 6 },
        { title: 'Best airlines', src: 'https://cdn.vuetifyjs.com/images/cards/plane.jpg', flex: 6 },
      ],
    }),
  }
</script>
<style>
@media print {
  @page{
    size: 8.5in 11in landscape;
  }
}</style>
