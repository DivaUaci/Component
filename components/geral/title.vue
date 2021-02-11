<template>
    <v-card
    class="mx-auto"
    max-width="344"
    >
  
    <v-list-item three-line>
      <v-list-item-content>
        <div class="overline mb-4">
            OLA {{ nome }}
        </div>
        <v-list-item-title class="headline mb-1">
          Welcome to Vuetify
        </v-list-item-title>
        <v-list-item-subtitle>a basic lesson for the use of Vuetify</v-list-item-subtitle>
      </v-list-item-content>

      <v-list-item-avatar
        tile
        size="80"
        color="grey"
      ></v-list-item-avatar>
      </v-list-item>
      </v-card>
          
</template>

<script lang='ts'>
import {Vue, Component, Emit, Prop} from 'nuxt-property-decorator'

@Component
export default class Title extends Vue {
    @Prop() nome! : string
}
</script>