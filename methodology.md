---
layout: page
title: How Does This Work?
description: Bagaimana alat ini dapat membantu orang tuli dalam berkomunikasi 
image: assets/images/glasses-architecture.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<section id="one">
  <div class="inner">
    <header class="major">
      <h1>Deskripsi Prototype</h1>
    </header>
    <h2 id="content">Pendekatan Desain</h2>
    Proyek ini mengadopsi pendekatan desain yang mengintegrasikan berbagai elemen teknologi modern untuk memastikan solusi yang inovatif, praktis, dan relevan. Fokus utama terletak pada pengembangan perangkat kacamata pintar Hearo Glasses yang dapat memenuhi kebutuhan aksesibilitas pengguna dengan gangguan pendengaran

    <h2 id="content">Key Points</h2>
    <dl>
      <dt>Konektivitas Terintegrasi</dt>
      <dd>
        <p>Kacamata ini dirancang untuk terhubung dengan perangkat lain seperti ponsel pintar, jam tangan pintar, dan perangkat IoT melalui teknologi Wi-Fi 6 dan Bluetooth 5.0. Disisi lain integrasi dari layanan Cloud memastikan proses inferensi real-time untuk live captioning.</p>
      </dd>
      <dt>Konsep Ubiquitous (Keberadaan di Mana-Mana)</dt>
      <dd>
        <p>Perangkat ini memastikan keberadaan teknologi di berbagai situasi dan lingkungan. Contohnya adalah tampilan informasi melalui Heads-Up Display (HUD) yang memanfaatkan Waveguide Optics untuk memastikan teks terlihat tanpa menghalangi pandangan. Teknologi ini mendukung sinkronisasi dengan perangkat lain untuk mengakses notifikasi  atau data penting secara real-time.</p>
      </dd>
      <dt>Contoh Pendekatan Konteks Aware</dt>
      <dd>
        <p>Perangkat dilengkapi fitur context awareness yang dapat mendeteksi lokasi, waktu, dan
kondisi lingkungan.</p>
      <h4>Alternate</h4>
      <ul class="alt">
        <li>Pengingat Kontekstual: Memberikan notifikasi berdasarkan lokasi pengguna, seperti
mengingatkan pembelian barang di toko tertentu.</li>
        <li>Penyesuaian Berdasarkan Kondisi Cahaya: Dengan bantuan Ambient Light
Sensor, kacamata ini mampu menyesuaikan tingkat kecerahan layar untuk kenyamanan
pengguna, seperti mengaktifkan mode malam secara otomatis.</li>
        <li>Pengenalan Konteks Suara: Perangkat dapat membedakan suara percakapan dan
pengumuman penting, serta memberikan respons yang relevan.</li>
      </ul>
      </dd>
    </dl>

    <h2 id="content">Rancangan Blok Arsitektur Prototype</h2>
    <span class="image fit">
      <img src="{% link /assets/images/diagram-architecture.png %}" alt="" />
    </span>

    <h2 id="content">Komponen Dasar Prototype</h2>
    <span class="image fit">
      <img src="{% link /assets/images/glasses-architecture.jpg %}" alt="" />
    </span>
    
    <h4>Key Points</h4>
		<ol>
			<li>Battery: Menyediakan daya dengan desain yang mendukung penggunaan jangka panjang.</li>
			<li>Magnetic Charging Port: Memungkinkan pengisian daya cepat dan aman.</li>
			<li>Touchpad Control: Memberikan kontrol navigasi intuitif.</li>
			<li>Indicator Lamp: Menampilkan status perangkat seperti konektivitas dan daya.</li>
			<li>Waveguide Optics: Memproyeksikan teks langsung ke lensa tanpa mengganggu pandangan.</li>
			<li>Camera: Menangkap visual untuk potensi fitur tambahan seperti pengenalan objek.</li>
      <li>Processor: Mengolah data suara menjadi teks dengan fitur context awareness.</li>
      <li>Microphone: Menangkap suara untuk diubah menjadi teks secara real-time.</li>
      <li>Speaker: Memberikan umpan balik suara opsional.</li>
      <li>Power Button: Mengontrol daya perangkat.</li>
      <li>Cable: Mendukung distribusi daya dan data antar komponen internal.</li>

		</ol>
    
    <h2>Video Presentation</h2>
    <div class="video-container">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/JLMfFfOvDx0?si=5MIXA16bR6pXIIuC"
        frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
    </div>
  </div>
</section>
