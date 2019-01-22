<template>
  <div class="header">
    <h1>{{ msg }}</h1>
    <p>
      Tracking
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <a class="button is-medium is-rounded is-warning" @click="">
      Ate Something
    </a>
    <a class="button is-medium is-rounded is-success" @click="alert">
      Felt Something
    </a>
    <a class="button is-medium is-rounded is-primary" @click="alert">
      Did Something
    </a>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
