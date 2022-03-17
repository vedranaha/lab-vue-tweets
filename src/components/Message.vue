<template>
<div>
  <p className="message">
    {{ message }}
  </p></div>
</template>

<script>
export default {
    name: "Message",
    props: {
        message: String,
    }
}
</script>