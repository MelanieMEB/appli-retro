<template>
  <div class="about">
    {{ message }}
  </div>
</template>

<script lang="ts">
  import { Vue } from "vue-property-decorator";

  export default class About extends Vue {
   message: string = 'Cette application a été réalisé pour vous aider à prévoir vos rétro'
  }
</script>

<style lang="scss">
#about {
  color: blue;
}
</style>