<template>
  <header class="header">
    <Logo />
    <NavBar />
    <SearchForm />
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from '../atoms'
import { NavBar, SearchForm } from '../molecules'

export default defineComponent({
  components: { Logo, NavBar, SearchForm }
})
</script>

<style scoped>
.header {
  width: 100%;
  display: grid;
  grid-template-columns: 160px repeat(2, auto);
  align-items: center;
  justify-content: space-between;
}
</style>
