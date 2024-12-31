<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaQuake Inside</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        h1, h2, h3 {
            color: #4CAF50;
        }

        .team {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .team-member {
            background: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
        }

        .team-member h4 {
            margin-bottom: 10px;
            font-size: 1.2em;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>JavaQuake Inside</h1>
    <p>Platform Pemantauan dan Analisis Gempa Bumi di Pulau Jawa</p>
</header>

<div class="container">
    <section>
        <h2>Latar Belakang</h2>
        <p>JavaQuake Inside adalah proyek yang bertujuan untuk memantau dan menganalisis gempa bumi di Pulau Jawa. Sistem ini dirancang untuk membantu masyarakat memahami pola gempa bumi dan meningkatkan kesiapsiagaan terhadap bencana.</p>
    </section>

    <section>
        <h2>Tujuan Proyek</h2>
        <ul>
            <li>Membuat sistem pemantauan gempa berbasis data yang akurat.</li>
            <li>Mengembangkan model prediksi gempa menggunakan Machine Learning.</li>
            <li>Menyediakan antarmuka pengguna yang mudah digunakan.</li>
            <li>Menyediakan laporan otomatis tentang risiko gempa berdasarkan lokasi.</li>
        </ul>
    </section>

    <section>
        <h2>Komponen Utama</h2>
        <ol>
            <li>Data Seismik Real-Time</li>
            <li>Analisis dan Prediksi</li>
            <li>Dashboard Interaktif</li>
            <li>Peringatan Dini</li>
        </ol>
    </section>

    <section>
        <h2>Anggota Tim</h2>
        <div class="team">
            <div class="team-member">
                <h4>Lutfi Julpian</h4>
                <p>Peran: Data Scientist</p>
                <p>Tanggung Jawab: Pengumpulan data, analisis data seismik, dan pengembangan model Machine Learning.</p>
            </div>
            <div class="team-member">
                <h4>Mohammad Faikar Natsir</h4>
                <p>Peran: Software Engineer</p>
                <p>Tanggung Jawab: Integrasi sistem pemantauan real-time dan pengembangan backend untuk dashboard.</p>
            </div>
            <div class="team-member">
                <h4>Rizka Amanda</h4>
                <p>Peran: UI/UX Designer</p>
                <p>Tanggung Jawab: Merancang antarmuka dashboard yang intuitif dan user-friendly.</p>
            </div>
            <div class="team-member">
                <h4>Andika Pratama</h4>
                <p>Peran: DevOps Engineer</p>
                <p>Tanggung Jawab: Menjamin ketersediaan sistem dan deployment aplikasi di cloud.</p>
            </div>
            <div class="team-member">
                <h4>Siti Nur Aisyah</h4>
                <p>Peran: Project Manager</p>
                <p>Tanggung Jawab: Mengelola timeline proyek, memastikan komunikasi yang efektif di antara tim, dan menjamin pencapaian target.</p>
            </div>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 Maetala Scientist | All Rights Reserved</p>
</footer>

</body>
</html>
