<template>
  <div class="home">
    <b-container>
    <ButtonComponent />
    <AlertComponent />
    <AspectComponent />
    <AvatarComponent />
  </b-container>
  </div>
</template>

<script>
// @ is an alias to /src
import ButtonComponent from '@/components/ButtonComponent.vue'
import AlertComponent from '@/components/AlertComponent.vue'
import AspectComponent from '@/components/AspectComponent.vue'
import AvatarComponent from '@/components/AvatarComponent.vue'

export default {
  name: 'HomeView',
  components: {
    ButtonComponent,
    AlertComponent,
    AspectComponent,
    AvatarComponent
  }
}
</script>
