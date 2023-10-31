<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Absensi Karyawan</title>
    <link rel="stylesheet" href="styles.css"> <!-- Hubungkan dengan file CSS jika ada -->
    <style>
        /* Gaya latar belakang situs */
        html {
            background-color: #f2f2f2; /* Ganti dengan warna latar belakang yang Anda inginkan */
        }

        /* Gaya header */
        header {
            background-color: #3498db; /* Ganti dengan warna header yang Anda inginkan */
            padding: 20px;
            text-align: center;
        }

        header h1 {
            color: #fff; /* Warna teks header */
        }

        /* Gaya logo */
        .logo {
            width: 150px;
            height: auto;
        }

        /* Gaya form */
        main {
            margin: 20px;
            background-color: #fff; /* Warna latar belakang form */
            padding: 20px;
            border-radius: 5px; /* Sudut elemen form dibuat lebih lembut */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Efek bayangan pada elemen form */
        }

        form label {
            display: block;
            margin-bottom: 5px;
        }

        form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc; /* Garis tepi input */
            border-radius: 5px; /* Sudut input dibuat lebih lembut */
        }

        form button {
            background-color: #3498db; /* Warna tombol Absen */
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        /* Gaya footer */
        footer {
            text-align: center;
            background-color: #3498db; /* Warna footer */
            padding: 10px;
            color: #fff; /* Warna teks footer */
        }
    </style>
</head>
<body>
    <header>
        <img class="logo" src="wahyu.png" alt="Logo Perusahaan Anda">
        <h1>Selamat Datang di Sistem Absensi Karyawan</h1>
        <p>Masukkan informasi absensi di bawah ini.</p>
    </header>

    <main>
        <form>
            <label for="nama">Nama Karyawan:</label>
            <input type="text" id="nama" name="nama" required>

            <label for="tanggal">Tanggal:</label>
            <input type="date" id="tanggal" name="tanggal" required>

            <label for="jam_masuk">Jam Masuk:</label>
            <input type="time" id="jam_masuk" name="jam_masuk" required>

            <label for="jam_pulang">Jam Pulang:</label>
            <input type="time" id="jam_pulang" name="jam_pulang" required>

            <button type="submit">Absen</button>
        </form>
    </main>

    <footer>
        <p>&copy; 2023 Nama Perusahaan Anda. Hak Cipta Dilindungi.</p>
    </footer>
</body>
</html>
