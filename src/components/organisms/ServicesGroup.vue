<template>
    <div class="services">
        <Services
        title="Front-end"
        description="aaaaaaaaaaaaaaaaaaaaaaaa
        aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa"/>
        <Services
        title="Front-end"
        description="aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
        aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa"/>
        <Services
        title="Front-end"
        description="aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
        aaaaaaaaaaaaaaaaaaaaaaaaaaaaa"/>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Services } from '../molecules'

export default defineComponent({
    components: {Services}
})
</script>

<style scoped lang="scss">
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>