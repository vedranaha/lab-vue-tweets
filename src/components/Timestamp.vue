<template>
   <span className="timestamp">{{ time }}</span>
</template>

<script>
export default {
    name: "Timestamp",
    props: {
        time: String,
    }
}
</script>