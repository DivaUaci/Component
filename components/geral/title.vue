<template>
    <v-card
    class="mx-auto"
    max-width="344"
    >
  
    <v-list-item three-line>
      <v-list-item-content>
        <div class="overline mb-4">
            Oi querida {{ nome }}
        </div>
        <v-list-item-title class="headline mb-1">
          Seja bem vinda 
        </v-list-item-title>
        <v-list-item-subtitle>Dia do amor vem ai, tire um tempinho pra si.</v-list-item-subtitle>
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
