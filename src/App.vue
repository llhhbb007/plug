<template>
  <div id="app">
    <calender :value="data" ></calender>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      data: ['2020,1,1','2020,3,6'],
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  justify-content: center;
}
body{
  padding: 0;
  margin: 0;
}
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
