<template lang='pug'>
    Title(:nome="nomeCompleto")
</template>

<script lang='ts'>
import {Component, Vue} from 'nuxt-property-decorator'
import Title from '../components/geral/title.vue'

@Component({
components: {
  Title
}
})
export default class extends Vue{
  nomeCompleto = "Diva Flora"
}
</script>

<style>
.myStyle {
  height: 500px;
  width: 300px;
  border: 1px solid red;
  margin: 0 auto;
}
</style>
