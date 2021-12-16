<template>
  <div>
    <nav class="navbar navbar-expand-lg">
      <a class="navbar-brand" href="#">Navbar</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Pricing</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Disabled</a>
          </li>
        </ul>
      </div>
    </nav>
    <header>
      <div class="jumbotron jumbotron-fluid d-flex align-items-center">
        <div class="container">
          <h1 class="display-4">SMKN 15 BANDUNG</h1>
          <p class="lead">
            This is a modified jumbotron that occupies the entire horizontal
            space of its parent.
          </p>
        </div>
      </div>
    </header>
    <h1 class="judul">Hello,I Am Muhammad Amirur</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar {
  background-color: #ff5403;
  height: 80px;
}
.nav-item {
  font-size: 20px;
  font-weight: bold;
}
.navbar-brand {
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  color: black;
}
.nav-link {
  display: flex;
  flex-direction: right;
  color: white;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  font-size: 25px;
}
#navbarNav .navbar-nav .nav-item a:hover {
  background-color: black;
  border-radius: 10%;
}
h1 {
  font-weight: bold;
  font-family: "Staatliches", cursive;

  text-align: center;
}
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
.judul {
  font: size 40px;
  font-family: Arial, Helvetica, sans-serif;
}
.jumbotron {
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("../assets/mountain.jpg");
  height: 1000px;
  width: 100%;
  color: white;
  position: 1000px;
}
</style>
