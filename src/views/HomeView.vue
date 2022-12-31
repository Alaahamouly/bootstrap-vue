<template>
  <div class="home">
    <b-container>
    <ButtonComponent />
    <AlertComponent />
  </b-container>
  </div>
</template>

<script>
// @ is an alias to /src
import ButtonComponent from '@/components/ButtonComponent.vue'
import AlertComponent from '@/components/AlertComponent.vue'

export default {
  name: 'HomeView',
  components: {
    ButtonComponent,
    AlertComponent
  }
}
</script>
