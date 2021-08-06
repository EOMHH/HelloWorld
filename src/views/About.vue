<template>
  <div class="about">
    <h1>This is an about page</h1>
    <el-button type="primary" size="default" @click="goto('/about/child')">跳转form</el-button>
  </div>
</template>
<script>
export default {
  data () {
    return {
    }
  },
  methods: {
    goto (url) {
      this.$router.push(
        {
          path: url
        })
    }
  }
}
</script>
