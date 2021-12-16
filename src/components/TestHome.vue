Template Fungsinya Untuk Menyimpan syntax-syntax HTML/Yang Berupa Framework
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
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
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

    <section class="content d-flex align-items-center justify-content-center">
      <div class="content-box">
        <h1>WELCOME TO MY SITE</h1>
      </div>
    </section>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
      <path
        fill="#0097e6"
        fill-opacity="1"
        d="M0,64L8,90.7C16,117,32,171,48,213.3C64,256,80,288,96,256C112,224,128,128,144,96C160,64,176,96,192,144C208,192,224,256,240,245.3C256,235,272,149,288,106.7C304,64,320,64,336,69.3C352,75,368,85,384,106.7C400,128,416,160,432,176C448,192,464,192,480,165.3C496,139,512,85,528,53.3C544,21,560,11,576,32C592,53,608,107,624,122.7C640,139,656,117,672,106.7C688,96,704,96,720,85.3C736,75,752,53,768,69.3C784,85,800,139,816,160C832,181,848,171,864,170.7C880,171,896,181,912,181.3C928,181,944,171,960,149.3C976,128,992,96,1008,101.3C1024,107,1040,149,1056,149.3C1072,149,1088,107,1104,90.7C1120,75,1136,85,1152,117.3C1168,149,1184,203,1200,208C1216,213,1232,171,1248,149.3C1264,128,1280,128,1296,112C1312,96,1328,64,1344,58.7C1360,53,1376,75,1392,80C1408,85,1424,75,1432,69.3L1440,64L1440,0L1432,0C1424,0,1408,0,1392,0C1376,0,1360,0,1344,0C1328,0,1312,0,1296,0C1280,0,1264,0,1248,0C1232,0,1216,0,1200,0C1184,0,1168,0,1152,0C1136,0,1120,0,1104,0C1088,0,1072,0,1056,0C1040,0,1024,0,1008,0C992,0,976,0,960,0C944,0,928,0,912,0C896,0,880,0,864,0C848,0,832,0,816,0C800,0,784,0,768,0C752,0,736,0,720,0C704,0,688,0,672,0C656,0,640,0,624,0C608,0,592,0,576,0C560,0,544,0,528,0C512,0,496,0,480,0C464,0,448,0,432,0C416,0,400,0,384,0C368,0,352,0,336,0C320,0,304,0,288,0C272,0,256,0,240,0C224,0,208,0,192,0C176,0,160,0,144,0C128,0,112,0,96,0C80,0,64,0,48,0C32,0,16,0,8,0L0,0Z"
      ></path>
    </svg>
  </div>
</template>
Script Fungsinya Untuk Mengolah Data
<script>
export default {
  name: "TestHome",
};
</script>
Style Merepresentasikan Bahasa Css Yang Berfungsi Untuk Merubah Tampilan Website
<style scoped>
.navbar {
  background-color: black;
}
.nav-link {
  color: white;
}
#navbarNav .navbar-nav .nav-item a:hover {
  background-color: orange;
  border-radius: 10%;
}
.navbar-brand {
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  color: White;
}

.content {
  width: 100%;
  height: 30vh;
  background-color: #0097e6;
}

.content .content-box h1 {
  color: #ffffff;
}
</style>
