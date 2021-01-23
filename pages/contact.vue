<template>
  <div></div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Page Title',
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          hid: 'description',
          name: 'description',
          content: 'My custom description',
        },
      ],
    }
  },
}
</script>

<style lang="scss" scoped></style>
