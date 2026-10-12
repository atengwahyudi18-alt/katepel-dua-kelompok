# KATEPEL Kuis Dua Kelompok

Aplikasi statis ini memakai GitHub Pages untuk halaman web dan Supabase Realtime untuk mengirim jawaban dari HP peserta ke layar proyektor.

## Menyiapkan Supabase

1. Buat proyek Supabase.
2. Salin **Project URL** dan **Publishable key** dari pengaturan proyek.
3. Buka aplikasi, masukkan URL dan publishable key pada panel sambungan, lalu simpan. Lakukan ini pada laptop dan pada setiap HP.
4. Jangan masukkan `secret key` atau `service_role key` ke aplikasi browser.

Aplikasi memakai Realtime Broadcast pada channel publik sementara bernama sesuai kode ruang. Data kuis hanya berada di memori layar penyelenggara. Kode ruang delapan digit dibagikan kepada dua HP; siapa pun yang mengetahui kode dapat bergabung ke ruang itu, jadi gunakan untuk kuis kelas dan jangan kirim informasi pribadi.

## Menerbitkan lewat GitHub Pages

1. Buat repository GitHub baru.
2. Unggah `index.html` ini ke root repository.
3. Di **Settings → Pages**, pilih sumber publikasi dari branch utama dan folder root.
4. Buka URL GitHub Pages yang diberikan. Gunakan URL yang sama di laptop dan kedua HP.
5. Di laptop, buat ruang dan tampilkan kode di proyektor. Di setiap HP, masukkan kode, pilih Sudut Merah atau Sudut Kuning, lalu jawab dengan A–D.

GitHub Pages hanya menayangkan file statis. Supabase Realtime yang menyinkronkan status jawaban ke layar proyektor.
