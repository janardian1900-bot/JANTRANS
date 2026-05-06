<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jantrans - Transportasi Karawang</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">JANTRANS</div>
            <p>Jasa Antar Jemput Bandara & Hotel - Area Karawang</p>
        </header>

        <section class="booking-card">
            <h3>Formulir Pemesanan</h3>
            <form id="formBooking">
                <div class="input-group">
                    <label>Nama Lengkap</label>
                    <input type="text" id="nama" placeholder="Masukkan nama Anda" required>
        # 🚖 Jantrans - Jasa Antar Jemput Karawang

**Jantrans** adalah aplikasi pemesanan transportasi sederhana yang dikhususkan untuk layanan antar-jemput antara **Hotel di area Karawang** dan **Bandara (Soekarno-Hatta/Halim)**.

## 🌟 Fitur Utama
- **Booking Mudah**: Form pemesanan yang simpel dan cepat.
- **Integrasi WhatsApp**: Pesanan langsung dikirim ke WhatsApp admin tanpa perlu login.
- **Responsif**: Tampilan nyaman dibuka melalui smartphone maupun komputer.
- **Area Layanan**: Fokus pada area industri dan perhotelan di Karawang.

## 🛠️ Teknologi yang Digunakan
- **HTML5**: Untuk struktur halaman.
- **CSS3**: Untuk desain visual yang modern dan profesional.
- **JavaScript**: Untuk logika pengolahan pesan dan integrasi API WhatsApp.
- **GitHub Pages**: Sebagai layanan hosting gratis.

## 📲 Cara Pemesanan
1. Buka link aplikasi Jantrans.
2. Isi Nama, Pilih Rute (Hotel ke Bandara atau sebaliknya).
3. Masukkan detail lokasi/hotel dan waktu penjemputan.
4. Klik tombol **"Kirim Pesanan via WhatsApp"**.
5. Admin Jantrans akan segera merespons untuk konfirmasi armada.

## 📞 Kontak Admin
- **WhatsApp**: [+62811925215](https://wa.me/62811925215)
- **Lokasi**: Karawang, Jawa Barat.

---
*Dibuat dengan bantuan Partner Coding untuk kemajuan UMKM transportasi Indonesia.*
            <input type="text" id="nama" placeholder="Masukkan nama Anda" required>
                </div>

                <div class="input-group">
                    <label>Pilih Layanan</label>
                    <select id="layanan">
                        <option value="Hotel ke Bandara">Penjemputan: Hotel ➔ Bandara</option>
                        <option value="Bandara ke Hotel">Penjemputan: Bandara ➔ Hotel</option>
                    </select>
                </div>

                <div class="input-group">
                    <label>Nama Hotel / Alamat Karawang</label>
                    <input type="text" id="lokasi" placeholder="Contoh: Resinda Hotel" required>
                </div>

                <div class="input-group">
                    <label>Tanggal & Jam Penjemputan</label>
                    <input type="datetime-local" id="waktu" required>
                </div>

                <button type="button" class="btn-wa" onclick="kirimPesan()">
                    Kirim Pesanan via WhatsApp
                </button>
            </form>
        </section>

        <footer>
            <p>© 2026 Jantrans Karawang. Aman, Nyaman, Tepat Waktu.</p>
        </footer>
    </div>

    <script src="script.js"></script>
</body>
</html>
