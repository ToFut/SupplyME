<template>
  <div class="hello">
    <button v-on:click="supply">ספקים</button>
    <button v-on:click="order">הזמנת סחורה</button>
    <button v-on:click="get">קבלת סחורה</button>

  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Supply Your Rest'
    }
  },
  methods: {
    order: function () {
      alert('order')
    },
    supply: function () {
      alert('supply')
    },
    get: function () {
      alert('get')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
