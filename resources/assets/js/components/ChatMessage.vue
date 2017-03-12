<template>
    <div>
        <p>{{ message.message }}</p>
        <small>{{ message.user.name }}</small>
    </div>
</template>

<script>
export default {
    // data() {
    //     return {
    //         message: "This is some message text",
    //         user: "jd"
    //     }
    // }
    props: ['message']
}
</script>