<template>
  <div>
    <app-server-status v-for="server in 5"></app-server-status>
  </div>
</template>
<script>
    import ServerStatus from "./ServerStatus";
    export default {
        // this is a local component.
        components: {
            'app-server-status': ServerStatus
        }
    }
</script>
