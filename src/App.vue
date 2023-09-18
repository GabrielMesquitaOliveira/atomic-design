<template>
  <div class="component">
    <Header/>
    <Presentation/>
    <ServicesGroup/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Header, Presentation, ServicesGroup } from './components/organisms'

export default defineComponent({
  components: { Header, Presentation, ServicesGroup }
})
</script>

<style lang="scss">
.component{
  margin: 5rem;
}
</style>
