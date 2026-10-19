# Jelajah Nutrien — Pendidikan Kesihatan Tahun 5

Aplikasi pembelajaran kendiri dalam satu fail HTML, menggunakan HTML5, CSS dan JavaScript tanpa pemasangan atau pelayan backend.

## Kandungan
- `index.html` — aplikasi lengkap: halaman utama, objektif, nota berperingkat, video YouTube, permainan pengukuhan, kuiz 25 soalan, maklum balas, bintang, lencana, laporan dan cetak/simpan PDF.
- `soalan_25.json` — salinan bank soalan dengan jawapan dan penerangan.

## Cara guna
1. Muat turun `index.html`.
2. Buka fail dalam pelayar moden (Chrome, Edge, Firefox atau Safari).
3. Masukkan nama murid dan tekan **Mula Pembelajaran**.
4. Audio suara menggunakan `speechSynthesis` Bahasa Melayu jika disokong oleh peranti/pelayar. Bunyi nada ringkas boleh jadi tidak tersedia pada sesetengah peranti.
5. Butang **Cetak / Simpan PDF** membuka dialog cetakan pelayar; pilih “Save as PDF” jika tersedia.

## Penerbitan melalui GitHub Pages
1. Log masuk ke GitHub dan cipta repositori baharu, contohnya `jelajah-nutrien-tahun5`.
2. Muat naik `index.html` ke akar repositori. Muat naik `soalan_25.json` jika mahu menyimpan bank soalan sebagai fail sumber berasingan.
3. Pergi ke **Settings → Pages**.
4. Pada bahagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, kemudian tekan **Save**.
6. Tunggu sehingga GitHub Pages memaparkan URL laman di halaman Settings → Pages. Gunakan URL yang diberikan GitHub; URL belum dicipta atau disahkan oleh pembangun ini.

## Nota kurikulum dan sumber
- DSKP KSSR Semakan 2017 Pendidikan Jasmani dan Pendidikan Kesihatan Tahun 5, bahagian Pemakanan, SK 8.1 dan SP 8.1.1–8.1.3. Rujukan yang boleh dibaca: https://fliphtml5.com/uwsyo/jvjb/DSKP_KSSR_SEMAKAN_2017_PENDIDIKAN_JASMANI_DAN_PENDIDIKAN_KESIHATAN_TAHUN_5/
- Video berkaitan: “PENDIDIKAN KESIHATAN TAHUN 5 | UNIT 12 | NUTRIEN KESIHATAN | Muka Surat 95–100”: https://www.youtube.com/watch?v=kgUDlZwZPWc
- Tajuk Unit 12 dirujuk daripada tajuk video pembelajaran yang ditemui. RPT berbeza mengikut sekolah/tahun; semak semula nama tema/unit dan susunan minggu dengan RPT rasmi sekolah sebelum digunakan sebagai dokumen perancangan formal.
- Nota dan soalan ialah bahan pengajaran asal yang disusun berdasarkan standard di atas, bukan salinan buku teks.

## Had dan privasi
- Video memerlukan sambungan internet.
- Kemajuan kuiz terakhir disimpan secara setempat dalam `localStorage` jika dibenarkan oleh pelayar. Tiada penghantaran markah kepada guru atau pelayan.
- Fungsi simpan laporan menggunakan dialog cetakan pelayar; tiada muat naik fail automatik.
