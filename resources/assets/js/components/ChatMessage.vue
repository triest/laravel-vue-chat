<template lang="html">
    <div class="chat-message">
        <p>{{ message.message }}</p>
        <small><b>{{ message.user.name }}</b></small>
    </div>
</template>

<script>
    export default {
        props: ['message']
    }
</script>

<style lang="css">
    .chat-message {
        padding: 1rem;
    }

    .chat-message > p {
        margin-bottom: .5rem;
    }
</style>
