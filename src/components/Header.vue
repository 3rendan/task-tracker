<template>
    <h1>{{ title }}</h1>
    <Button text="Add Task" color="green" />
</template>

<script>
import Button from './Button.vue';

export default {
  name: 'HeaderX',
  props: {
    title: String,
  },
  components: {
    Button,
  }
}
</script>
<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
</style>