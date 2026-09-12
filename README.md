# catatan-transaksi-agen
Aplikasi pencatatan transaksi Agen BRILINK dengan Supabase.

## Setup Supabase

1. Buat project baru di [Supabase](https://supabase.com/).
2. Buka **SQL Editor**, lalu jalankan seluruh isi [supabase.sql](supabase.sql).
3. Di Supabase, buka **Project Settings > API** dan salin **Project URL** serta ** anon public key**.
4. Buka [index.html](index.html), lalu isi `SUPABASE_URL` dan `SUPABASE_ANON_KEY` pada konfigurasi JavaScript.
5. Buka aplikasi lewat server lokal, misalnya ekstensi Live Server. Jangan gunakan service role key di browser.
6. Buat akun lewat tombol **Buat Akun**. Jika konfirmasi email aktif, konfirmasi email sebelum masuk.

Data transaksi dan saldo dilindungi Row Level Security. Setiap akun hanya dapat membaca dan mengubah data miliknya sendiri.
