<template name='my-button'>
  <button @click='handleClick'>
    按钮
  </button>
</template>

<script>
  export default {
    methods: {
      handleClick() {
        console.log('你点击了按钮！');
      }
    }
  }
</script>