<template>
  <div>
    <svg-icon icon-class="github" @click="goto" />
  </div>
</template>

<script>
export default {
  name: 'HduCloudGit',
  data() {
    return {
      url: 'https://gitee.com/tony2y/HduCloud-flowable'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
