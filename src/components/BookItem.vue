<template>
  <li>{{ book.title }}: {{ book.author }}</li>
</template>
<script>
export default {
  name: "Book Item",
  props: [
    "book"
  ]
}
</script>

<style>
  li{
    display: block;
    margin: 0 10px;
  }
</style>
