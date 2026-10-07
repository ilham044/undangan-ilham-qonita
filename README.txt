ILHAM & QONITA — WEDDING INVITATION
====================================

CARA MEMASUKKAN FOTO, VIDEO, DAN MUSIK

1. Foto cerita:
   assets/images/story.jpg

2. Foto prewedding:
   assets/images/prewed1.jpg
   assets/images/prewed2.jpg
   assets/images/prewed3.jpg
   assets/images/prewed4.jpg
   assets/images/prewed5.jpg
   assets/images/prewed6.jpg

3. Video:
   assets/video/prewedding.mp4

4. Musik:
   assets/music/music.mp3

5. WhatsApp RSVP:
   Buka index.html dengan Notepad/VS Code.
   Cari:
       const phone='6281234567890';
   Ganti dengan nomor WhatsApp tujuan, format internasional tanpa +.

6. Data acara:
   Di index.html cari bagian "The Wedding" dan ubah tanggal, jam, dan lokasi sesuai acara.

CARA TEST:
- Double click index.html.
- Klik "Buka Undangan".
- Musik akan mencoba diputar setelah klik.
- Scroll untuk melihat gallery, video, dan RSVP.

CARA UPLOAD KE GITHUB PAGES:
1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ZIP ini (index.html + folder assets).
3. Settings > Pages.
4. Source: Deploy from a branch.
5. Pilih branch main dan folder /root.
6. Save.
7. GitHub akan memberikan alamat undangan Anda.

CATATAN:
- Jangan ubah struktur folder assets.
- Untuk web yang ringan, kompres video MP4 terlebih dahulu.
- Musik autoplay browser hanya aman dimulai setelah interaksi pengguna; karena itu musik diputar ketika tombol "Buka Undangan" diklik.

7. FOTO CALON MEMPELAI:
   assets/images/groom.jpg = foto utama Ilham
   assets/images/bride.jpg = foto utama Qonita
   assets/images/groom1.jpg - groom3.jpg = album Ilham
   assets/images/bride1.jpg - bride3.jpg = album Qonita

8. TURUT MENGUNDANG:
   Edit bagian "Turut Mengundang" di index.html.
   Ganti [Nama Keluarga] dengan nama keluarga sebenarnya.
   Jumlah nama bisa ditambah dengan menyalin baris <li>...</li>.
