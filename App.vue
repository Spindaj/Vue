<div id="app">
  <h1>{{ nome }}</h1>
  <input type="text" v-model="nome" />
</div>
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<script type="text/javascript">
  const vue = new Vue({
    el: '#app',
    data: {
      nome: 'Hello World!'
    }
  })
</script>