<template>
  <div @click="click">
    <img v-if="type !== 'cat'" src="http://www.codemash.org/wp-content/themes/codemash/images/codemash-icon.png" alt="code-mash">
    <img v-else src="http://www.codemash.org/wp-content/themes/codemash/images/view-blog-image.png" alt="code-mash-cat">
  </div>
</template>

<script>
export default {
  props: ['type'],

  methods: {
    click () {
      this.$emit('logo-click', {})
    }
  }
}
</script>
