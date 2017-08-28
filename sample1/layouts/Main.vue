<template>
  <div class="container">
    <ul>
      <li>
        <v-link href="/sample1/">Home</v-link>
        <v-link href="/sample1/about">About</v-link>
      </li>
    </ul>

    <slot></slot>
  </div>
</template>

<script>
  import VLink from '../components/VLink.vue'

  export default {
    components: {
      VLink
    }
  }
</script>

