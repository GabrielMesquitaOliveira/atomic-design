<template>
    <div class="services">
        <h2 class="title">{{ title }}</h2>
        <p class="description">{{ description }}</p>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    props: {
        title: {type: String, required: true},
        description: {type: String, required: true},
    }
})
</script>

<style scoped lang="scss">
.services {
  display: flex;
  flex-direction: column;
  .title {
    color: #935e92;
    font-weight: bold;
    margin-bottom: 0.8rem;
  }
  .description {
    color: #293947;
    line-height: 1.5;
  }
}
</style>