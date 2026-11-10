# Roda Nasib – Spin Wheel Pembagian Tugas

Web spin wheel untuk membagi tugas kelompok secara acak. Satu file HTML, bisa dibuka langsung di browser tanpa server.

## Cara pakai
1. Buka `index.html` di browser.
2. Tulis nama anggota di kotak kanan, satu nama per baris.
3. Klik **PUTAR!** di tengah roda.

## Fitur
- Roda pastel dengan animasi melambat, drum roll, getar, dan suara "kaget" (`kaget.wav`).
- Popup pemenang dengan confetti dan kalimat acak.
- Keluarkan pemenang dari roda otomatis (bisa dimatikan).
- Riwayat urutan terpilih + tombol salin untuk grup WA.
- 8 karakter DC mengorbit roda (gambar di folder `karakter/`, fallback kartun SVG jika gambar tidak ada).
- Daftar nama tersimpan otomatis di browser (localStorage).

## Struktur
- `index.html` – halaman jadi (hasil generate).
- `build.py` – generator halaman + gambar kartun SVG. Jalankan `python build.py` setelah mengubahnya.
- `karakter/*.png` – gambar karakter (batman, flash, superman, cyborg, wonderwoman, greenlantern, robin, joker).
- `kaget.wav` – suara saat pemenang muncul (`kaget.mp3` = file asli sebelum dipotong heningnya).
