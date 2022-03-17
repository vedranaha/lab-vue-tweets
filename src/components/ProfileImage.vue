<template>
  <img
      :src="src"
      className="profile"
      alt="profile"
    />
</template>

<script>
export default {
    name: "ProfileImage",
    props: {
        src: String,
    },
}
</script>