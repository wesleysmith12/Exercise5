<template>
    <div class="container">
        <app-header></app-header>
        <hr>
        <div class="row">
            <app-server></app-server>
            <app-server-details></app-server-details>
        </div>
        <hr>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import Header from './Header.vue'
    import Footer from './Footer.vue'
    import Server from './Server.vue'
    import ServerDetails from './ServerDetails.vue'

    export default {
        components: {
            'app-header': Header,
            'app-footer': Footer,
            'app-server': Server,
            'app-server-details': ServerDetails
        }
    }
</script>

<style>

</style>
