<template>
  <div class="portfolio">
    <header>
      <h1>My Portofolio</h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Hobby</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>

    
    <main>
      <img src="@/assets/WhatsApp Image 2024-04-02 at 2.22.27 PM.jpeg">
      
      <section class="about">
        <br>
        <h2>About Me</h2>
        <p>Halo! Perkenalkan saya Nurul Hayana Putri, dari Pekanbaru,
          tanggal lahir 19 April 2003, saya sedang menempuh pendidikan di Universitas Islam Riau di Jurusan Teknik Informatika dijurusan ini saya ingin mengembangkan web developer</p>
      </section>

      <section class="projects">
        <h2>Skill dan Kemampuan</h2>
        <div class="project">
          <h3>Hobby: Memasak</h3>
        </div>
        <br>
        <div class="project">
          <h2>Pengalaman</h2>
          <p>Pernah mengikuti organisasi disekolah yaitu OSIS dan MPK</p>
        </div>
      </section>

    </main>
    <footer>
      <p>&copy; 2024 My Portofolio Nurul Hayana Putri</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
nav {
  margin-left: auto; 
  margin-right: -700px; 
}


h1 {
  
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-align: center;
  /* Menengahkan teks */
  font-size: 40px;
  font-weight: bold;
  color: #ffffff;
  margin-bottom: 20px;
  padding-top: 20px;
  padding-bottom: 20px;
  border-bottom: 1px solid #ffffff;
}

h2 {
  color: #ffffff;
}

nav {
  margin-left: auto;
  /* Memindahkan elemen navigasi ke kanan */
}

.portfolio {
  font-family: Arial, sans-serif;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #ffffff;
}

img {
  border-radius: 100%;
  width: 150px;
  height: 150px;
}

section {
  margin-bottom: 40px;
}

footer {
  margin-top: 10px;
  text-align: center;
  color: #777;
  text-align: center;
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>
