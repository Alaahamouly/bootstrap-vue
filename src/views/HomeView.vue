<template>
  <div class="home">
    <ButtonComponent />
  </div>
</template>

<script>
// @ is an alias to /src
import ButtonComponent from '@/components/ButtonComponent.vue'

export default {
  name: 'HomeView',
  components: {
    ButtonComponent
  }
}
</script>
