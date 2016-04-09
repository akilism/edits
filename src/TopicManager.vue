<template>
  <ul class="topic-list">
    <li v-for="topic in topics">
      {{ topic }}
    </li>
  </ul>
</template>

<script>
export default {
  data () {
    return {};
  },
  methods: {
  },
  props: ['topics']
}
</script>

<style>
.topic-list {
  position: absolute;
  top: 200px;
  left: 100px;
  z-index: 100;
  background: white;
  border: 1px solid black;
  padding: 20px;
  list-style: none;
}
</style>
