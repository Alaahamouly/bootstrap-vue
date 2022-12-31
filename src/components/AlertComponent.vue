<template>
    <div class="alert">
        <h3>** b-alert **</h3>
        <b-alert show>Default Alert!</b-alert>
        <hr />
        <b-alert show variant="success">Success Alert!</b-alert>
        <hr />
        <b-alert show variant="danger" dismissible>Dismissible danger alert!</b-alert>
        <hr />
        <b-alert :show="toggleAlertStatus" variant="warning" >Toggle alert!</b-alert>
        <span style="cursor: pointer" @click="toggleAlert">Toggle alert!</span>
    </div>
</template>
<script>
export default {
    name: 'AlertComponent',
    data() {
        return {
            toggleAlertStatus: false,
        }
    },
    methods: {
        toggleAlert() {
            this.toggleAlertStatus = !this.toggleAlertStatus
        }
    }
}
</script>