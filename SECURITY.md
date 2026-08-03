# Kebijakan Keamanan

Kebijakan ini berlaku sebagai default untuk repositori organisasi Maubisa (`maubisa-id`) yang belum
punya `SECURITY.md` sendiri. Repositori dengan kebijakan sendiri memakai versinya sendiri.

## Melaporkan kerentanan

**Jangan** membuat issue publik untuk laporan keamanan. Laporkan secara privat lebih dulu supaya
bisa kami perbaiki sebelum diketahui luas.

- Email: **security@maubisa.id** (atau **no-reply@maubisa.id** bila belum tersedia).
- Sertakan: deskripsi kerentanan, langkah reproduksi, dampak yang mungkin, dan versi atau URL yang
  terpengaruh.

Mohon beri kami waktu wajar untuk menanggapi dan memperbaiki sebelum mengungkap ke publik. Kami
menghargai pelaporan yang bertanggung jawab.

## Yang perlu diketahui

- Rahasia (kunci API, kata sandi, connection string) tidak pernah kami simpan di dalam kode. Semua
  kredensial hidup di environment.
- Untuk detail kontrol keamanan per proyek, lihat `SECURITY.md` di repositori terkait, misalnya
  [account-center-starter/SECURITY.md](https://github.com/maubisa-id/account-center-starter/blob/main/SECURITY.md).
