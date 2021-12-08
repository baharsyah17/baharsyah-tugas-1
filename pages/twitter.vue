<template>
  <div id="app">
    <nav>
      <ul>
        <li class="px-40">Tugas Bahar</li>
        <li><a href="/">Home</a></li>
        <li><a href="/facebook">Facebook</a></li>
        <li><a href="/twitter">Twitter</a></li>
        <li><a href="youtube">Youtube</a></li>
      </ul>
    </nav>
    <h1>Akses Menuju Twitter</h1>
    <a href="https://twitter.com/?lang=en">
      <center><button>Twitter</button></center>
    </a>
  </div>
</template>

<script>
export default {};
</script>

<style>
ul {
  margin: 0;
  overflow: hidden;
  background-color: black;
  color: white;
  padding: 20px;
}
li {
  float: left;
}
li a {
  display: block;
  text-align: center;
  border-radius: 5px;
  padding-left: 25px;
  padding-right: 25px;
}
li a:hover:not(.active) {
  background-color: blue;
}
h1 {
  text-align: center;
  font-size: 30px;
}
button {
  text-align: center;
  display: block;
  background: aqua;
  color: white;
  padding: 20px;
  border-radius: 20px;
}
</style>
