<template>
<div>
  <input type="checkbox" id="toodo-item" checked="false" />
  <label for="todo-item">My Todo Item</label>
</div>
</template>

<script>
export default {
  props: {
    label: { required: true, type: String },
    done: { default: false, type: Boolean }
  }
};
</script>


<style scoped>

</style>