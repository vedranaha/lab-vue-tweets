<template>
<div>
  <img
      :src="src"
      className="profile"
      alt="profile"
    />
</div>
</template>

<script>
export default {
    props: {
        src: String,
    },
}
</script>