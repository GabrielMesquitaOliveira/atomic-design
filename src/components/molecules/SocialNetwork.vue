<template>
  <div class="social-network">
    <SocialLink name="Github" url="github.com" icon="github.svg"/>
    <SocialLink name="Twitter" url="twitter.com" icon="twitter.svg"/>
    <SocialLink name="Facebook" url="facebook.com" icon="facebook.svg"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '../atoms'

export default defineComponent({
  components: { SocialLink }
})
</script>

<style scoped>
.social-network {
  display: grid;
  grid-gap: 1rem;
}
</style>
