<template>
  <div id="app">
    <Navbar />

    <main>
      <section
        id="home"
        class="hero d-flex align-items-center justify-content-start text-start text-white"
      >
        <div class="gradient-to-right">
          <div class="gradient-to-bottom">
            <div class="container">
              <h1 class="selamat">Selamat Datang Di</h1>
              <h1 class="display-3 text-shadow fw-semibold" >
                Unggas Jaya
              </h1>
              <p class="sambutan">
                Terima kasih telah mempercayai Unggas Jaya sebagai pilihan terbaik untuk kebutuhan unggas Anda.
                Pusat unggulan untuk produk unggas yang bergizi, berkualitas, dan higienis.
                Kami senang menjadi bagian dari setiap hidangan yang Anda sajikan!
              </p>
              <p class="lead text-shadow fw-light">
                Bergizi, Berkualitas, dan Higienis
              </p>
              <a href="#about" class="btn hero-btn">Tentang Unggas Jaya</a>
            </div>
          </div>
        </div>
      </section>

      <section class="pt-10" id="about">
        <h2 class="about-h2">TENTANG UNGGAS JAYA</h2>
        <div class="stats-container">
          <div class="stat-item">
            <h1 class="stat-h1">7000+</h1>
            <p class="stat-p">Ekor Ayam</p>
          </div>
          <div class="stat-item-middle">
            <h1 class="stat-h1">1984</h1>
            <p class="stat-p">Berdiri Sejak 1984</p>
          </div>
          <div class="stat-item">
            <h1 class="stat-h1">260+</h1>
            <p class="stat-p">260kg/hari</p>
          </div>
        </div>
        <p class="text-center">
          Kami percaya bahwa makanan sehat dimulai dari sumbernya. Di Unggas
          Jaya, kami menerapkan sistem peternakan organik yang menjunjung tinggi
          kesejahteraan hewan dan kelestarian lingkungan. Setiap butir telur
          kami adalah hasil dari proses produksi yang alami, tanpa menggunakan
          hormon pertumbuhan, antibiotik, atau pestisida
        </p>
        <div class="vision-mission row">
          <div class="vision text-center col-lg-6">
            <h3>Visi</h3>
            <p>Menjadi perusahaan unggas terkemuka yang menyediakan produk BERGIZI, BERKUALITAS, dan HIGIENIS untuk mendukung kesehatan masyarakat, serta berkontribusi pada pemenuhan kebutuhan pangan nasional dengan standar terbaik.</p>
          </div>
          <div class="mission mx-auto w-md-50 col-lg-6">
            <h3>Misi</h3>
            <ul>
              <li>
                  <p>
                    Memproduksi dan Menyediakan Produk Unggas Berkualitas Tinggi
Mengembangkan dan memelihara standar produksi yang tinggi untuk memastikan setiap produk unggas yang dihasilkan memiliki kualitas terbaik dan kaya gizi.
                  </p>
              </li>
              <li>
                  <p>
                    Menerapkan Praktik Produksi yang Higienis
Melakukan proses produksi yang mematuhi standar kebersihan dan keamanan pangan yang ketat, guna menjamin kesehatan konsumen.
                  </p>
              </li>
              <li>
                <p>
                  Berperan Aktif dalam Pembangunan Berkelanjutan
Mengintegrasikan praktik pertanian yang berkelanjutan dan ramah lingkungan dalam semua aspek operasional perusahaan untuk mendukung kesejahteraan masyarakat dan lingkungan.
                </p>
              </li>
            </ul>
          </div>
        </div>
      </section>

      <section class="pt-10" id="services">
        <h2>Tentang Kami</h2>
        <div class="services-container">
          
          <div class="card">
            <div class="card-image">
              <img src="./assets/card-1.jpg" alt="Card Image">
            </div>
            <div class="card-content">
              <h2 class="card-title">Telur Eceran</h2>
              <p class="card-text">
                PT Unggas Jaya adalah mitra terpercaya dalam penyediaan telur segar secara grosir untuk kebutuhan bisnis Anda. Kami menyediakan telur berkualitas tinggi langsung dari peternakan unggas terbaik, dengan proses produksi yang memenuhi standar kebersihan dan keamanan pangan.
              </p>
              <a href="#" class="card-button">Pelajari Lebih Lanjut</a>
            </div>
          </div>

          <div class="card">
            <div class="card-image">
              <img src="./assets/card-2.jpeg" alt="Card Image">
            </div>
            <div class="card-content">
              <h2 class="card-title">Telur Grosir</h2>
              <p class="card-text">
                Telur unggulan PT Unggas Jaya adalah pilihan sempurna untuk memenuhi kebutuhan protein harian Anda. Diproduksi dari peternakan unggas yang dikelola dengan standar kebersihan dan kualitas tinggi
              </p>
              <a href="#" class="card-button">Pelajari Lebih Lanjut</a>
            </div>
          </div>

          <div class="card">
              <div class="card-image">
                <img src="./assets/card-3.jpg" alt="Card Image">
              </div>
              <div class="card-content">
                <h2 class="card-title">Ayam Petelur</h2>
                <p class="card-text">
                  PT Unggas Jaya menyediakan ayam petelur berkualitas tinggi yang dirawat dengan standar peternakan modern untuk menghasilkan telur yang sehat dan bergizi. Kami berkomitmen memberikan solusi terbaik bagi peternak maupun konsumen yang membutuhkan ayam petelur produktif dan bernilai ekonomis.
                </p>
                <a href="#" class="card-button">Pelajari Lebih Lanjut</a>
              </div>
          </div>

        </div>
      </section>

      <section class="pt-10" id="testimonials">
        <h2>Testimonials</h2>
        <div class="testimonials-container row">
          <div class="testimonial-card col-12 col-lg-4 col-md-6">
            <p>
              "Layanan dan produk dari PT Unggas Jaya benar-benar unggul! Kami sangat puas dengan kualitas ayam potong dan telur yang mereka sediakan. Tidak hanya itu, tim mereka selalu responsif dan membantu dalam setiap pemesanan, sehingga kami merasa dihargai sebagai pelanggan. Terima kasih, PT Unggas Jaya, atas komitmen Anda dalam menyediakan produk unggas yang sehat dan berkualitas!"
            </p>
            <span>— Agus setiawan</span>
          </div>
          <div class="testimonial-card col-12 col-lg-4 col-md-6">
            <p>
              "Kami telah bekerja sama dengan PT Unggas Jaya selama lebih dari dua tahun, dan mereka selalu konsisten dalam memberikan produk unggas dengan standar tertinggi. Semua produk datang tepat waktu dan selalu dalam kondisi segar. Sangat direkomendasikan untuk siapa saja yang membutuhkan pasokan unggas berkualitas."
            </p>
            <span>— Naura maulid</span>
          </div>
          <div class="testimonial-card col-12 col-lg-4 col-md-6">
            <p>
              "Kualitas unggas dari PT Unggas Jaya memang tak tertandingi. Tim mereka profesional dan berdedikasi, dan kualitas produk yang mereka kirimkan selalu memenuhi standar yang kami harapkan. Kami merasa beruntung bisa menjalin kerja sama jangka panjang dengan perusahaan yang begitu terpercaya dan fokus pada kepuasan pelanggan."
            </p>
            <span>— Supraman tejo</span>
          </div>
        </div>
      </section>

      <section class="pt-10" id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-container">
          <div class="carousel">
            <div class="slide"><img src="./assets/card-2.jpeg" alt="Gallery Image 1" /></div>
            <div class="slide"><img src="./assets/card-3.jpg" alt="Gallery Image 1" /></div>
            <div class="slide"><img src="./assets/card-1.jpg" alt="Gallery Image 1" /></div>
            <!-- Tambahkan lebih banyak slide sesuai kebutuhan -->
          </div>
          <button class="prev">&lt;</button>
          <button class="next">&gt;</button>
        </div>
      </section>

      <section class="pt-10" id="contact">
        <h2>Hubungi Kami</h2>
        <p class="text-center">
          Untuk informasi lebih lanjut, jangan ragu untuk menghubungi kami kapan
          saja!
        </p>
        <div class="d-flex justify-content-center">
          <a href="mailto:pt.unggasjayasejahtera@gmail.com" class="btn btn-danger w-25"
            >Send us an Email</a
          >
        </div>
      </section>
    </main>

    <footer>
      <div class="footer-content">
        <div class="footer-section">
          <h3>Unggas Jaya</h3>
          <p>Bergizi, Berkualitas, dan Higienis</p>
        </div>
        <div class="footer-section">
          <h3>Kontak</h3>
          <p>
            Jalan Tambak Saji 1, Gedungan Barat, Desa Gedungan, Kecamatan
            Batuan, Kabupaten Sumenep
          </p>
          <p>085331494781</p>
          <p>pt.unggasjayasejahtera@gmail.com</p>
        </div>
        <div class="footer-section row d-grid justify-content-center">
          <h3 class="col">Follow Us</h3>
          <div class="social-icons col">
            <a
              href=""
              class="icon-facebook"
              ><Facebook size="20"
            /></a>
            <a
              href=""
              class="icon-instagram"
              ><Instagram size="20"
            /></a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
import { Instagram, Facebook } from "lucide-vue-next";
import Navbar from "./components/Navbar.vue";
</script>

<style>

html {
  overflow-x: hidden !important;
}
/* Add your styles here */
body {
  overflow-x: hidden !important;
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
}

header {
  background-color: rgb(255, 87, 26);
  padding: 1rem 1rem;
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 1000;
}

.gradient-to-right{
  background: linear-gradient(to right, #0000009e, transparent);
  height: 100vh;
  width: 100%;
  position: absolute;
}

.gradient-to-bottom{
  background: linear-gradient(to top, rgb(229,222,206), transparent);
  margin-top: 55vh;
  height: 45vh;
  width: 100%;
  position: absolute;
}

.hero {
  height: 100vh;
  padding: 0 20px;
}

.hero .container {
  margin-top: auto;
  position: absolute;
  bottom: 4rem; /* Jarak maksimum dari bawah */
  left: 20px;
}

.selamat{
  margin: 0;
  font-size: 2rem;
  line-height: 0.5;
}

.sambutan{
  color: whitesmoke;
  font-size: 1.2rem;
  max-width: 70%;
  line-height: 1.6;
}

.lead{
  color: whitesmoke;
}

.text-start {
  text-align: left;
}

.hero .btn {
  background-color: rgb(255, 255, 255);
  color: #000;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s ease,color 0.3s ease;
}

.hero .btn:hover {
  background-color:   rgb(255, 118, 68);
  color: #ffffff;
}

.text-shadow {
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

.bg-green {
  background-color: transparent 50;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 2rem;
}

.navbar-brand {
  display: flex;
  align-items: center;
}

.logo-img {
  width: auto;
  height: 50px;
}

main {
  background-color: rgb(229,222,206);
  margin-top: 60px;
  width: 100% !important;
  padding: 0 !important;
  margin: 0 !important;
  max-width: 100% !important;
}

.hero {
  background-image: url("./assets/hero-bg.jpg");
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}

body {
  font-family: Arial, sans-serif;
  background-color: #2b2b2b;
  color: #fff;
}

/* About */
.about-h2{
  font-size: 4rem;
  color:  rgb(31,38,40);
  padding-bottom: 0,7rem;
}

.stats-container {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  gap: 2rem; /* Space between items */
  padding: 1rem 2rem 2rem 2rem;
  text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.5);
}

.stat-item-middle{
  border-right: 2px solid rgba(255, 255, 255, 0.3);
  border-left: 2px solid rgba(255, 255, 255, 0.3);
  padding: 0rem 1.5rem;
  transition: transform 0.8s ease-in-out; 
  transform: scale(1);
}

.stat-item-middle:hover{
  transform: scale(1.1);
}

.stat-item{
  transition: transform 0.8s ease-in-out; 
  transform: scale(1);
}

.stat-item:hover{
  transform: scale(1.1);
}

.stat-item:last-child {
  border-right: none;
}

.stat-h1{
  color: rgb(71,78,76);
}

.stat-p{
  color: rgba(239,174,141);
  font-weight: 600;

}
/* row about */
h1 {
  font-size: 5rem;
  color: rgb(31,38,40);
  margin: 0;
  font-weight: 700;
}

p {
  font-size: 1.2rem;
  color: rgb(31,38,40);
  margin-top: 0.5rem;
}


section {
  padding: 2rem;
}

.pt-10 {
  padding-top: 5.1rem;
  margin: 0rem 5rem;
  background-color: rgb(229,222,206);
}


h2,
h3 {
  color:rgb(31,38,40);
  text-align: center;
}

.services-container {
  padding-top: 1rem;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

/* card */
.card {
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 6px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  max-width: 370px;
  margin: 2rem;
  overflow: hidden;
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.card-image img {
  width: 100%;
  height: auto;
  max-height: 12rem;
  border-bottom: 1px solid #ddd;
  transition: transform 0.3s ease;
}

.card-image img:hover {
  transform: scale(1.05);
}

.card-content {
  padding: 20px;
  text-align: center;
}

.card-title {
  font-size: 24px;
  font-weight: bold;
  color: #333;
}

.card-text {
  font-size: 16px;
  color: #666;
  margin: 10px 0;
}

.card-button {
  display: inline-block;
  padding: 10px 20px;
  font-size: 16px;
  font-weight: bold;
  color: #fff;
  background-color: rgb(255, 87, 26);
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.card-button:hover {
  background-color: #e04c1b;
}

.service-card {
  flex-basis: 30%;
  margin-bottom: 2rem;
  padding: 1rem;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  background-color: white;
  border-radius: 8px;
  transition: transform 0.2s;
}

.service-card:hover {
  transform: translateY(-5px);
}

.services-container,
.testimonials-container,
.gallery-container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.service-card,
.testimonial-card {
  flex-basis: 30%;
  margin-bottom: 2rem;
  padding: 1rem;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Gallery */
#gallery {
  text-align: center;
  padding: 2rem;
}

.gallery-container {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
  overflow: hidden;
}

.carousel {
  display: flex;
  transition: transform 0.5s ease-in-out;
}

.slide {
  min-width: 100%;
  transition: transform 0.5s ease;
}

.slide img {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

button.prev,
button.next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: rgba(255, 255, 255, 0.5);
  border: none;
  padding: 1rem;
  cursor: pointer;
  font-size: 1.5rem;
}

button.prev {
  left: 10px;
}

button.next {
  right: 10px;
}

button.prev:hover,
button.next:hover {
  background-color: rgba(255, 87, 26, 0.7);
}

/* footer */

footer {
  background-color: rgb(255, 87, 26);
  color: white;
  padding: 2rem;
}

.footer-content {
  display: flex;
  justify-content: space-between;
}

.footer-section {
  flex-basis: 30%;
}

.social-icons a {
  color: white;
  margin-right: 1rem;
  text-decoration: none;
}
</style>
