<template>
  <div class="presentation">
    <SocialNetwork />
    <img class="presentation" src="../../assets/images/presentation.svg" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialNetwork } from '../molecules'

export default defineComponent({
  components: { SocialNetwork }
})
</script>

<style scoped>
.presentation {
  margin-top: 2rem;
  position: relative;
  display: grid;
  justify-content: center;
  .presentation {
    width: 80%;
    justify-self: center;
  }
}
.social-network {
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
}
</style>
