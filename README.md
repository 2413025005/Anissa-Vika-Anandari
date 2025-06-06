<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portofolio Anissa Vika</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    body {
      margin: 0;
      font-family: 'Quicksand', sans-serif;
      background-color: #FFF7F9;
      color: #5E474B;
    }

    header {
      background-color: #FBEFF5;
      text-align: center;
      padding: 30px 20px;
      border-bottom: 3px solid #E8C1C6;
    }

    header h1 {
      margin: 0;
      font-size: 28px;
      color: #A25F69;
    }

    nav {
      text-align: center;
      margin: 10px 0 20px;
    }

    nav a {
      margin: 0 14px;
      text-decoration: none;
      color: #A25F69;
      font-weight: bold;
      font-size: 15px;
    }

    section {
      max-width: 800px;
      margin: auto;
      padding: 40px 20px;
    }

   .profile-wrapper {
  background-color: #fff0f4;
  background-image: url('https://www.transparenttextures.com/patterns/paper-fibers.png');
  background-repeat: repeat;
  background-size: auto;
  padding: 25px;
  border-radius: 20px;
  box-shadow: 0 0 20px rgba(196, 143, 150, 0.1);
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: center;
}



    .profile-pic {
      width: 130px;
      aspect-ratio: 1 / 1;
      border-radius: 50%;
      border: 4px solid #C48F96;
      object-fit: cover;
      display: block;
      background-color: #fff;
      transition: transform 0.3s ease;
      box-shadow: 0 4px 12px rgba(196, 143, 150, 0.3);
    }

    .profile-pic.active {
      transform: scale(1.1) rotate(3deg);
    }

    .box {
      background-color: #FAF1F4;
      border-radius: 12px;
      padding: 25px;
      margin-bottom: 30px;
      text-align: center;
    }

    .box img {
      width: 150px;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    .box a {
      display: inline-block;
      margin: 5px;
      padding: 6px 14px;
      background-color: #C48F96;
      color: white;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }

    .box a:hover {
      background-color: #b3737c;
    }

    h2 {
      text-align: center;
      color: #A25F69;
      margin-bottom: 30px;
    }

    h3 {
      color: #A25F69;
    }

    .social-icons {
      margin-top: 15px;
    }

    .social-icons a {
      font-size: 26px;
      margin: 10px;
      color: #874C57; /* Lebih gelap, biar jelas */
      text-decoration: none;
      transition: 0.3s;
    }

    .social-icons a:hover {
      color: #E0939F;
    }

    footer {
      background-color: #FBEFF5;
      color: #A25F69;
      text-align: center;
      padding: 15px;
      font-size: 14px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Portofolio Anissa Vika Anandari</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#profile">Profile</a>
    <a href="#project">Project</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="profile">
    <h2>Profile</h2>
 <div class="profile-wrapper" style="flex-direction: column;">
  <img src="vika.jpg" alt="Foto Anissa" class="profile-pic" id="foto">
  <div style="text-align: center; margin-top: 10px;">
    <h2 style="margin: 0 0 5px;">Anissa Vika Anandari</h2>
    <p style="margin: 0;">2413025005</p>
  </div>
</div>


    <div class="box" style="margin-top: 25px;">
      <h3>About Me</h3>
      <p>Hello everyone!</p>
	<p>Saya Anissa Vika Anandari dengan NPM 2413025005, mahasiswi dari program studi S1 Pendidikan Teknologi Informasi 2024 kelas A di Universitas Lampung.</p>
      <p>Website ini adalah portofolio digital berisi kumpulan tugas mata kuliah <b>Grafika Komputer</b></p>
    </div>
  </section>

  <section id="project">
    <h2>Project</h2>

    <div class="box">
      <h3>Tugas 1: Tokoh Grafika Komputer</h3>
	<p>"John Warnock"</p>
      <img src="warnock.jpg" alt="Tokoh">
      <br>
      <a href="https://drive.google.com/file/d/1N7PYFLz_4oL8o718eW4Sy_Yuc6BfM7Rg/view?usp=drive_link">Ppt</a>
      <a href="https://drive.google.com/file/d/1VGaGp10ZNzutUida9dTLIwgQQmCBkTGO/view?usp=drive_link">Laporan</a>
      <a href="https://youtu.be/sYdIRuUfiQE.com">Video</a>
    </div>

    <div class="box">
      <h3>Tugas 2: Algoritma Pembentukan Garis</h3>
	<p>"Garis DDA dan Bresenham"</p>
      <img src="garis.png" alt="Garis">
      <br>
      <a href="garisDDA.html">Hasil</a>
      <a href="https://drive.google.com/file/d/10IlipPBpydOVmPrl6Fcwkz8kScuxIgqM/view?usp=drive_link">Laporan</a>
      <a href="https://youtu.be/ikyS6RBk2xs.com">Video</a>
    </div>

    <div class="box">
      <h3>Tugas 3: Algoritma Pembentukan Lingkaran</h3>
	<p>"Lingkaran Bresenham dan Midpoint"</p>
      <img src="lingkaran.png" alt="Lingkaran">
      <br>
      <a href="lingkaran.html">Hasil</a>
      <a href="https://drive.google.com/file/d/1_GtyUVohvVCC_1HKTmOtJ0-phX_ipXrJ/view?usp=drive_link">Laporan</a>
      <a href="https://youtu.be/OjhdSKjeJlU?si=akS_kpzPNL3tvxFd">Video</a>
    </div>

    <div class="box">
      <h3>Tugas 4: Algoritma Pembentukan Kurva</h3>
	<p>"Kurva Bezier"</p>
      <img src="kurva.png" alt="Kurva">
      <br>
      <a href="kurva.html">Hasil</a>
      <a href="https://drive.google.com/file/d/1gHam6Cg_8LngdIASssa_JBv03PA5S2Xr/view?usp=drive_link">Laporan</a>
      <a href="https://youtu.be/mMj6PnlUfXw">Video</a>
    </div>

    <div class="box">
      <h3>Kuis 1: Persamaan Misteri</h3>
	<p>"Kurva Berbentuk Hati"</p>
      <img src="heart.png" alt="Kurva hati">
      <br>
      <a href="heart.html">Hasil</a>
      <a href="https://drive.google.com/file/d/1PEg2nlYoYMlqyynkxC7vn1ViSwCJdYZ0/view?usp=drive_link">Laporan</a>
    </div>

    <div class="box">
      <h3>Kuis 2: Transformasi</h3>
	<p>"Matriks Transformasi 2D"</p>
      <img src="geotran.png" alt="Geogebra">
      <br>
      <a href="https://docs.google.com/spreadsheets/d/1-yundq1EazIuDpzjYt3sV0SwDzDCM4Tes0uQvhrMJXg/edit?usp=sharing">Spreadsheet</a>
      <a href="https://drive.google.com/file/d/1U551QOPHqIAzBckeg3roHGmKz01usnYD/view?usp=sharing">Laporan</a>
      <a href="https://youtu.be/n1K5GeJ-CrM">Video</a>
    </div>

    <div class="box">
      <h3>Kuis 3: Line Clipping Algorithm</h3>
	<p>"Cohen-Clip"</p>
      <img src="geoline.png" alt="Geogebra">
      <br>
      <a href="https://docs.google.com/spreadsheets/d/1PseJoHM__GeoV2O8CUCVVn74Yz0zKBrxOoL6sCCaQBM/edit?usp=sharing">Spreadsheet</a>
      <a href="https://drive.google.com/file/d/1I2j_OBD3DXd2tz1R020W_zA63TWyZ13d/view?usp=drive_link">Laporan</a>
      <a href="https://youtu.be/W-inpTsb1Qk">Video</a>
    </div>

    <div class="box">
      <h3>Kuis 4: Polygon Clipping Algorithm</h3>
	<p>"Sutherland–Hodgman & Weiler–Atherton"</p>
      <img src="polygon.png" alt="#">
      <br>
      <a href="https://docs.google.com/presentation/d/1u2AScSK0dYkkMFEpnJEIRbVEWDHBE-L8/edit?usp=drive_link&ouid=113573758752583581302&rtpof=true&sd=true">Ppt</a>
      <a href="https://drive.google.com/file/d/1Ib7yto4J7k45nmACErRv3Yina42Of99f/view?usp=drive_link">Laporan</a>
      <a href="https://youtu.be/SPKmU2iB2Ls">Video</a>
    </div>
    

  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="box">
      <p>Hubungi saya melalui:</p>
      <div class="social-icons">
        <a href="https://wa.me/6285789228233" target="_blank" title="WhatsApp"><i class="fab fa-whatsapp"></i></a>
        <a href="mailto:anissavika@gmail.com" target="_blank" title="Email"><i class="fas fa-envelope"></i></a>
        <a href="https://id.linkedin.com/in/anissa-vika-anandari-b3a53032b" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
        <a href="https://www.instagram.com/ansvika__?igsh=MTFzZGp2cjN3Y2tkOQ==" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
        <a href="https://youtube.com/@ansvikaa?si=Tr8XkW8dRLHehZOA" target="_blank" title="YouTube"><i class="fab fa-youtube"></i></a>
      </div>
    </div>
  </section>

  <footer>
    Created by Anissa Vika Anandari • 2025
  </footer>

  <script>
    const foto = document.getElementById('foto');
    foto.addEventListener('click', () => {
      foto.classList.toggle('active');
    });
  </script>

</body>
</html>
