<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      <b>For do manifest,</b><br>
      
      <a href="https://www.oprahdaily.com/life/a30244004/how-to-manifest-anything/" target="_blank" rel="noopener">7 Steps for Manifesting</a>.
    </p>
    <h3>For do affirmation,</h3>
    <ul>
      <li><a href="https://www.oprahdaily.com/life/relationships-love/g25629970/positive-affirmations/">Daily Affirmation</a></li>
      <li><a href="https://www.mindtools.com/air49f4/using-affirmations" target="_blank" rel="noopener">Using Affirmations</a></li>
    </ul>
  
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
p {
  color: #c51350;
}
h1 {
  color: #ff7e67;
}
h3 {
  margin: 50px 0 0;
  color: #c51350;
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
  color: #9c42e1;
}
</style>
