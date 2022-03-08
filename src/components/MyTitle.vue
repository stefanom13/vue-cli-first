<template>
  <div class="title">
      <h2>{{title}}</h2>
  </div>
</template>

<script>
export default {
    // name:"MyTitle",
    data ( ) {
      return {
        title:'La mia prima app con Vue CLI!'
      }
    }
}
</script>

<style lang="scss" scoped>

.title{
 color: rebeccapurple;
}

</style>
