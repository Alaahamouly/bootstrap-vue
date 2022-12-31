<template>
  <div class="avatar">
    <h3>** b-avatar **</h3>
    <b-avatar src="https://placekitten.com/300/300" size="24px" class="me-2"></b-avatar>
    <b-avatar src="https://placekitten.com/310/310" :size="32" class="me-2"></b-avatar>
    <b-avatar src="https://placekitten.com/320/320" size="6rem" class="me-2"></b-avatar>
    <b-avatar src="https://placekitten.com/330/330" class="me-2"></b-avatar>
    <hr />
    <b-avatar icon="star-fill" size="3rem" class="me-2"></b-avatar>
    <b-avatar square size="3rem" class="me-2">Vue</b-avatar>
    <b-avatar rounded size="3rem" variant="primary" class="me-2"></b-avatar>
    <b-avatar badge size="3rem" variant="primary" class="me-2"></b-avatar>
    
  </div>
</template>

<script>
export default {
    name: 'AvatarComponent'

}
</script>

<style>

</style>