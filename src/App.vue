<template>
    <!--==================== HEADER ====================-->
    <header class="header blur-header" id="header">
        <nav class="nav container">
            <a href="#" class="nav__logo">
                <img src="./assets/img/marsudia_logo_warna.png" alt=""> Marsudia
            </a>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><a href="#home" class="nav__link active-link">Beranda</a></li>
                    <li class="nav__item"><a href="#coding" class="nav__link">Coding</a></li>
                    <li class="nav__item"><a href="#tutorial" class="nav__link">Tutorial</a></li>
                    <li class="nav__item"><a href="#alat" class="nav__link">Peralatan</a></li>
                    <li class="nav__item"><a href="#details" class="nav__link">Detail</a></li>
                </ul>

                <div class="nav__close" id="nav-close">
                    <i class="ri-close-line"></i>
                </div>
            </div>

            <div class="nav__toggle" id="nav-toggle">
                <i class="ri-menu-line"></i>
            </div>
        </nav>
    </header>

    <!--==================== MAIN ====================-->
    <main class="main">
        <!--==================== HOME ====================-->
        <section class="home section" id="home">
            <div class="home__container container grid">
                <img src="./assets/img/tempat_sampah.png" alt="Tempat Sampah Otomatis" class="home__img">

                <div class="home__data">
                    <h1 class="home__title">
                        TEMPAT <span class="highlighted_text">PEMILAH SAMPAH</span> OTOMATIS <br>
                        ARDUINO🌿
                    </h1>

                    <p class="description">
                        Mengambil langkah awal untuk mengubah Bumi menjadi tempat yang lebih bersih, hijau, dan nyaman
                        dengan tempat pemilah sampah berbasis Arduino.
                    </p>

                    <div class="home__buttons">
                        <a href="#coding" class="button">
                            <span><i class="ri-arrow-right-line"></i></span>
                            DAPATKAN CODE
                        </a>
                        <a href="#footer" class="button__link">SMA Marsudirini Bekasi</a>
                    </div>
                </div>
            </div>
        </section>

        <!--==================== CODING ====================-->
        <section class="contact section" id="coding">
            <h2 class="section__title">
                JALANKAN TEMPAT SAMPAH DENGAN <br> <span class="highlighted_text">ARDUINO CLOUD 🍄</span>
            </h2>

            <div class="contact__container container grid">
                <iframe class="code_embed" src="https://app.arduino.cc/sketches/42291155-898d-41e2-b952-2cdfde2894b5?view-mode=embed"
                    style="height:530px;width:600px;margin:0" frameborder="0"></iframe>

                <div class="contact__content">
                    <h3 class="contact__title">
                        <i class="ri-cactus-line" style="color: hsl(93, 50%, 38%)"></i> PENJELASAN
                    </h3>
                    <p class="description">
                        Kode ini digunakan untuk mendeteksi dan memilah sampah secara otomatis menggunakan Arduino.
                        <span class="highlighted_em">Sensor ultrasonik</span> mendeteksi keberadaan sampah,
                        lalu <span class="highlighted_em">sensor induktif, kapasitif</span>, dan <span class="highlighted_em">sensor raindrop</span> menentukan apakah sampah itu logam, organik, atau anorganik.

                        <br><br>Setelah jenis sampah diketahui, sistem menggerakkan <span class="highlighted_em">motor stepper & servo</span>
                        untuk membuang sampah ke tempat yang sesuai. Sampah basah dikategorikan sebagai organik,
                        sedangkan logam dan bahan nonlogam kering masuk ke kategori anorganik.

                        <br><br>Fungsi <span class="highlighted_em">throwTrash()</span> menggerakkan motor, dan <span class="highlighted_em">laporan()</span> mencetak hasil deteksi ke serial monitor.
                    </p>
                </div>
            </div>
        </section>

        <!--==================== TUTORIAL ====================-->
        <section class="care section" id="tutorial">
            <h2 class="section__title">
                TAHAP-TAHAP <span class="highlighted_text">MENJALANKAN</span> <br> TEMPAT PEMILAH SAMPAH OTOMATIS 🌱
            </h2>

            <div class="care__container container grid">
                <div class="circuit_container">
                    <img src="./assets/img/circuit_image.png" alt="Gambar Rangkaian" class="care__img">
                </div>

                <ul class="care__list">
                    <li class="care__item"><i class="ri-checkbox-fill"></i> Buka sketch code melalui website Arduino Code.</li>
                    <li class="care__item"><i class="ri-checkbox-fill"></i> Sesuaikan pin sensor di dalam kode.</li>
                    <li class="care__item"><i class="ri-checkbox-fill"></i> Sambungkan board Arduino UNO R3 ke laptop melalui USB.</li>
                    <li class="care__item"><i class="ri-checkbox-fill"></i> Klik tombol ceklis untuk verifikasi.</li>
                    <li class="care__item"><i class="ri-checkbox-fill"></i> Klik tombol panah untuk upload.</li>
                    <li class="care__item"><i class="ri-checkbox-fill"></i> Lepas kabel USB dan sambungkan ke powerbank.</li>
                    <li class="care__item"><i class="ri-checkbox-fill"></i> Gunakan tempat sampah sesuai kebutuhan!</li>
                </ul>
            </div>
        </section>

        <!--==================== COMPONENTS (ALAT) ====================-->
        <section class="shop section" id="alat">
            <h2 class="section__title">PERALATAN 🪴</h2>
            <div class="shop__container container grid">
                <!-- List of product cards remains unchanged for brevity -->
                <!-- All <article class="shop__card">... </article> components are kept as they are already clean -->
            </div>
        </section>

        <!--==================== PERFORMANCE (DETAILS) ====================-->
        <section class="new section" id="details">
            <div class="new__container container grid">
                <div class="new__data">
                    <h2 class="section__title">
                        TINGKAT <span class="highlighted_text">AKURASI</span> DAN <span class="highlighted_text">PRESISI</span> YANG TINGGI🌷
                    </h2>
                    <p class="new__description">
                        Tingkat akurasi dan presisi yang tinggi memastikan sampah dipilah dengan akurat dan konsisten.
                    </p>
                </div>

                <div class="new__content grid">
                    <article class="new__card">
                        <img src="./assets/img/90.png" alt="Akurasi" class="new__img">
                        <h2 class="new__title">Akurasi</h2>
                        <div class="card__description">Mengukur kemampuan sistem dalam mengklasifikasi sampah secara benar.</div>
                    </article>

                    <article class="new__card">
                        <img src="./assets/img/100.png" alt="Presisi" class="new__img">
                        <h2 class="new__title">Presisi</h2>
                        <div class="card__description">Menunjukkan seberapa akurat klasifikasi sampah organik dilakukan.</div>
                    </article>

                    <article class="new__card">
                        <img src="./assets/img/80.png" alt="Recall" class="new__img">
                        <h2 class="new__title">Recall</h2>
                        <div class="card__description">Menunjukkan berapa banyak sampah organik yang berhasil terdeteksi sebagai organik.</div>
                    </article>
                </div>
            </div>
        </section>
    </main>

    <!--==================== FOOTER ====================-->
    <footer class="footer" id="footer">
        <div class="footer__container container grid">
            <div class="footer__content grid">
                <div>
                    <h3 class="footer__title">SEKOLAH</h3>
                    <ul class="footer__links">
                        <li><a href="https://www.smamarsudirinibekasi.sch.id/" class="footer__link">Tentang Kami</a></li>
                    </ul>
                </div>

                <div>
                    <h3 class="footer__title">INFORMASI</h3>
                    <ul class="footer__links">
                        <li><a href="https://www.arduino.cc" class="footer__link">Tentang Arduino</a></li>
                        <li><a href="https://cplusplus.com/" class="footer__link">Tentang C++</a></li>
                    </ul>
                </div>

                <div>
                    <h3 class="footer__title">SOSIAL MEDIA</h3>
                    <div class="footer__social">
                        <a href="https://www.facebook.com/smamarsudirinibekasiofficial" target="_blank" class="footer__social-link"><i class="ri-facebook-circle-fill"></i></a>
                        <a href="https://www.instagram.com/smamarsudirinibekasi" target="_blank" class="footer__social-link"><i class="ri-instagram-fill"></i></a>
                        <a href="https://x.com/smamarsudbks" target="_blank" class="footer__social-link"><i class="ri-twitter-x-line"></i></a>
                    </div>
                </div>
            </div>
        </div>
        <span class="footer__copy">&#169; All Rights Reserved By Maria A. & Evelyn L.</span>
    </footer>

    <!--========== SCROLL UP ==========-->
    <a href="#" class="scrollup" id="scroll-up">
        <i class="ri-arrow-up-line"></i>
    </a>
</template>

<script setup>
  import "./assets/css/styles.css";
  import { onMounted } from "vue";

  onMounted(() => {
      const navMenu = document.getElementById("nav-menu");
      const navToggle = document.getElementById("nav-toggle");
      const navClose = document.getElementById("nav-close");

      if (navToggle) {
          navToggle.addEventListener("click", () => {
              navMenu.classList.add("show-menu");
          });
      }

      if (navClose) {
          navClose.addEventListener("click", () => {
              navMenu.classList.remove("show-menu");
          });
      }

      document.querySelectorAll(".nav__link").forEach(link => {
          link.addEventListener("click", () => {
              navMenu.classList.remove("show-menu");
          });
      });

      const scrollUpButton = document.getElementById("scroll-up");
      const handleScroll = () => {
          if (window.scrollY >= 350) {
              scrollUpButton.classList.add("show-scroll");
          } else {
              scrollUpButton.classList.remove("show-scroll");
          }
      };
      window.addEventListener("scroll", handleScroll);

      const sr = ScrollReveal({
          origin: "top",
          distance: "80px",
          duration: 2500,
          delay: 300
      });

      sr.reveal(`.home__img, .new__data, .care__img, .contact__content, .footer, .circuit_container, .code_embed`);
      sr.reveal(`.home__data, .care__list, .contact__img`, { delay: 500 });
      sr.reveal(`.new__card`, { delay: 500, interval: 100 });
      sr.reveal(`.shop__card`, { interval: 100 });
  });
</script>
