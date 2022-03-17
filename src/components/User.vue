<template>
  <span className="user">
    <span className="name">{{ userData.name }}</span>
    <span className="handle">{{ userData.handle }}</span>
  </span>
</template>

<script>
export default {
    name: "User",
    props: {
        userData: Object,
    },
    mounted() {
      console.log(this.userData)
    }
}
</script>