<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Engineering Manager & Digital Nomad</h2>
    <ul>
      <li>
        <a
          href="https://www.facebook.com/nomad.mitya"
          target="_blank"
        >
          facebook
        </a>
      </li>
      <li>
        <a
          href="https://www.linkedin.com/in/dgladyshev/"
          target="_blank"
        >
          linkedin
        </a>
      </li>
      <li>
        <a
          href="https://www.instagram.com/mitya_gladyshev"
          target="_blank"
        >
          instagram
        </a>
      </li>
      <li>
        <a
          href="https://github.com/dgladyshev"
          target="_blank"
        >
          github
        </a>
      </li>
      <br>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Mitya Gladyshev'
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
