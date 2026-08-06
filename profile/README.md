<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/maubisa-id/account-center-starter/main/.github/assets/maubisa-logo-white.png">
  <img alt="Maubisa" src="https://raw.githubusercontent.com/maubisa-id/account-center-starter/main/.github/assets/maubisa-logo.png" height="64">
</picture>

# Maubisa

**Belajar dan bertumbuh, untuk pelajar Indonesia.**

EdTech asal Indonesia yang menemani dari cemas menjadi lulus, dari penasaran menjadi mahir. Semua
produk kami berdiri di atas satu identitas, satu pembayaran, dan satu pengalaman.

<p>
  <a href="https://maubisa.id"><img alt="Website" src="https://img.shields.io/badge/Website-maubisa.id-0a48b7?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://akun.maubisa.id"><img alt="Pusat akun" src="https://img.shields.io/badge/Pusat%20akun-akun.maubisa.id-1f6feb?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://demo-akun.maubisa.id"><img alt="Coba demo" src="https://img.shields.io/badge/Coba%20demo-2ea44f?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

<p>
  <a href="https://nextjs.org/"><img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white"></a>
  <a href="https://react.dev/"><img alt="React" src="https://img.shields.io/badge/React-149ECA?logo=react&logoColor=white"></a>
  <a href="https://www.typescriptlang.org/"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white"></a>
  <a href="https://laravel.com/"><img alt="Laravel" src="https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white"></a>
  <a href="https://www.prisma.io/"><img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white"></a>
  <a href="https://docs.midtrans.com/"><img alt="Midtrans" src="https://img.shields.io/badge/Midtrans-Core%20API-0B7BE9"></a>
  <img alt="Dibuat di Indonesia" src="https://img.shields.io/badge/dibuat%20di-Indonesia-E11D48">
</p>

<p>
  <a href="#tentang-maubisa">Tentang</a> &nbsp;·&nbsp;
  <a href="#untuk-siapa">Audiens</a> &nbsp;·&nbsp;
  <a href="#ekosistem-produk">Produk</a> &nbsp;·&nbsp;
  <a href="#cara-semuanya-terhubung">Arsitektur</a> &nbsp;·&nbsp;
  <a href="#open-source">Open source</a> &nbsp;·&nbsp;
  <a href="#prinsip-kami">Prinsip</a> &nbsp;·&nbsp;
  <a href="#ikut-berkontribusi">Kontribusi</a> &nbsp;·&nbsp;
  <a href="#komunitas-dan-dukungan">Dukungan</a>
</p>

</div>

---

> [!TIP]
> **Ingin melihat karya kami secara langsung? Coba [demo-akun.maubisa.id](https://demo-akun.maubisa.id).**
> Masuk sebagai user `budi@example.com` atau admin `admin@maubisa.id` (sandi `password123`), atau
> daftar akun baru lalu cek email yang masuk di kotak email demo. Semua pembayaran memakai mode
> sandbox, jadi aman dicoba tanpa uang asli.

## Tentang Maubisa

**Maubisa** (PT Litera Edu Solusi) adalah platform EdTech asal Indonesia. Kami membantu pelajar dan
lulusan berpikir, membaca, dan menulis lebih baik, lewat bimbingan, kelas, webinar, dan komunitas.
Payung besarnya adalah **MBG (Maubisa Beyond Growth)**, yaitu belajar yang tumbuh bersama
penggunanya.

Kami membangun produk yang saling terhubung, bukan aplikasi yang berdiri sendiri-sendiri. Satu akun
membuka semua layanan, satu pusat pembayaran mencatat semua transaksi, dan tiap produk fokus pada
pengalamannya sendiri. Karakter kami hangat, kredibel, dan tidak terburu-buru, seperti mentor yang
menemani sampai selesai.

## Untuk siapa

Kami membangun untuk tiga orang yang nyata:

- **Mahasiswa tingkat akhir** yang butuh bimbingan skripsi dan tesis. Sering cemas soal tenggat,
  sensitif harga, dan kebanyakan mengakses lewat ponsel.
- **Lulusan baru dan profesional muda** yang ingin menambah keahlian dan menaikkan karier. Terbiasa
  cepat dan menghargai proses yang jelas.
- **Profesional** yang mengejar sertifikasi resmi. Menilai kredibilitas dengan teliti sebelum
  memutuskan membayar.

## Ekosistem produk

| Produk | Untuk apa | Model | Status |
|--------|-----------|-------|:------:|
| **Maubisa Lulus** | Bimbingan skripsi dan akademik, dari diskusi harian sampai latihan sidang | Bayar per paket | Berjalan |
| **MBG+** | Langganan belajar: video, Reading Notes, AI Prompt Library, komunitas | Langganan bulanan | Dikembangkan |
| **MBG Space** | Webinar dan kelas gratis | Gratis | Berjalan |
| **MBG Forge** | Webinar dan workshop berbayar | Bayar per acara | Berjalan |
| **Kelas dan Sertifikasi** | Kelas praktik plus jalur sertifikasi resmi | Bayar per kelas | Rencana |
| **Akun Maubisa** | Satu login (SSO) dan pusat pembayaran untuk semua layanan | Gratis | Berjalan |

## Cara semuanya terhubung

Bayangkan satu kartu anggota yang berlaku di semua toko dalam satu grup. Maubisa bekerja seperti itu.
Kami menyebutnya pola hub-and-spoke: satu tulang punggung untuk akun dan pembayaran, dengan banyak
produk di sekelilingnya.

```
                     +----------------------------+
                     |       Akun Maubisa          |   Satu identitas.
                     |  identitas + pembayaran     |   Satu pembayaran.
                     |  + hak akses (SSO)          |   Sumber kebenaran.
                     +----------------------------+
                       ^           ^           ^
             login + hak akses + tagihan (per pengguna)
                       |           |           |
                   Maubisa       MBG+        Kelas
                    Lulus      (belajar)     (LMS)
```

- **Satu identitas.** Daftar sekali, langsung masuk ke semua produk lewat SSO.
- **Satu pembayaran.** Semua pembelian lewat satu pusat checkout, jadi riwayat dan hak akses tampil
  di satu tempat.
- **Produk terpisah, data terpisah.** Tiap layanan punya databasenya sendiri dan hanya menunjuk ke
  identitas pusat. Masalah di satu produk tidak menyeret produk lain.

> [!NOTE]
> **Hanya webhook pembayaran yang boleh membuka akses.** Harga selalu dihitung di server, bukan
> dari halaman atau URL. Akses baru terbuka setelah Midtrans mengabari bahwa bayarnya lunas, dan
> pesan itu diverifikasi keasliannya lebih dulu. Tombol "sukses" di browser tidak pernah dipercaya.

## Open source

Beberapa bagian tersulit saat membangun produk kami rilis sebagai template open-source, langsung
dari kode yang kami pakai di produksi. Tujuannya menghemat waktu tim lain yang menghadapi masalah
yang sama.

<table>
<tr><td>

### [account-center-starter](https://github.com/maubisa-id/account-center-starter)

Pusat akun berbasis **Next.js** plus checkout **Midtrans Core API** dengan tampilan yang bisa diatur
sesuai merek Anda. Mendukung QRIS, Virtual Account, e-wallet, kartu dengan 3D Secure, langganan, dan
kartu tersimpan. Siap produksi, lisensi MIT.

<p>
  <a href="https://github.com/maubisa-id/account-center-starter/generate"><img alt="Gunakan template ini" src="https://img.shields.io/badge/gunakan%20template%20ini-2ea44f?logo=github&logoColor=white"></a>
  <a href="https://demo-akun.maubisa.id"><img alt="Demo langsung" src="https://img.shields.io/badge/demo%20langsung-0a48b7?logo=vercel&logoColor=white"></a>
  <a href="https://github.com/maubisa-id/account-center-starter/blob/main/LICENSE"><img alt="Lisensi" src="https://img.shields.io/github/license/maubisa-id/account-center-starter?color=3FB950&label=lisensi"></a>
  <a href="https://github.com/maubisa-id/account-center-starter/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/maubisa-id/account-center-starter?style=flat&color=3FB950"></a>
  <a href="https://github.com/maubisa-id/account-center-starter/releases/latest"><img alt="Rilis" src="https://img.shields.io/github/v/release/maubisa-id/account-center-starter?color=3FB950&label=rilis"></a>
</p>

Cocok kalau Anda butuh halaman akun untuk pelanggan, dashboard langganan, atau halaman bayar sendiri
yang tampil sama di semua produk. Coba dalam satu menit:

```bash
npx degit maubisa-id/account-center-starter akun-saya
cd akun-saya
npm install
cp .env.example .env    # minimal isi BETTER_AUTH_SECRET
npm run dev             # http://localhost:3000
```

</td></tr>
<tr><td>

### [thesisdesk](https://github.com/maubisa-id/thesisdesk)

Sistem manajemen bimbingan skripsi berbasis **Next.js** dan **Prisma**, kode yang sama yang kami
pakai di produksi untuk [thesis.maubisa.id](https://thesis.maubisa.id). Dashboard per peran, progres
bab (Kanban), jadwal sesi dengan Google Meet otomatis, dokumen berversi dengan anotasi, chat, dan
modul akademik kampus opsional (SSO OIDC, integrasi SIAKAD, sidang akhir, multi-tenant). Siap
produksi, lisensi AGPL-3.0.

<p>
  <a href="https://github.com/maubisa-id/thesisdesk/generate"><img alt="Gunakan template ini" src="https://img.shields.io/badge/gunakan%20template%20ini-2ea44f?logo=github&logoColor=white"></a>
  <a href="https://thesis.maubisa.id"><img alt="Demo langsung" src="https://img.shields.io/badge/demo%20langsung-0a48b7?logo=vercel&logoColor=white"></a>
  <a href="https://github.com/maubisa-id/thesisdesk/blob/main/LICENSE"><img alt="Lisensi" src="https://img.shields.io/github/license/maubisa-id/thesisdesk?color=3FB950&label=lisensi"></a>
  <a href="https://github.com/maubisa-id/thesisdesk/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/maubisa-id/thesisdesk?style=flat&color=3FB950"></a>
  <a href="https://github.com/maubisa-id/thesisdesk/releases/latest"><img alt="Rilis" src="https://img.shields.io/github/v/release/maubisa-id/thesisdesk?color=3FB950&label=rilis"></a>
</p>

Cocok kalau Anda butuh sistem bimbingan skripsi/tesis untuk kampus, program studi, atau tim
bimbingan mandiri, siap jalan tanpa branding kami. Coba dalam satu menit:

```bash
npx degit maubisa-id/thesisdesk thesis-saya
cd thesis-saya
npm install
cp .env.example .env    # minimal isi BETTER_AUTH_SECRET
npm run db:setup && npm run seed
npm run dev             # http://localhost:3100
```

</td></tr>
</table>

## Yang kami pakai

| Bidang | Teknologi |
|--------|-----------|
| Aplikasi | Next.js, React, TypeScript, Tailwind CSS, Astro (situs utama) |
| Data | Prisma, MySQL (Cloud SQL) |
| Auth | Better Auth (email dan password, 2FA, OTP), SSO lewat cookie domain |
| Pembayaran | Midtrans Core API, Payment Link, Subscription API |
| Konten | Directus (headless CMS) |
| Backend produk | Laravel (Maubisa Lulus) |
| Infrastruktur | Docker, Coolify, Cloudflare, Google Cloud Storage |
| Monitoring | Sentry |

## Repositori

Ekosistem kami terbagi antara dua template terbuka dan beberapa aplikasi produk internal.

```
maubisa-id/
├─ account-center-starter   publik, MIT       pusat akun + checkout Midtrans Core API
├─ thesisdesk               publik, AGPL-3.0  bimbingan skripsi (dipakai di thesis.maubisa.id)
├─ .github                  publik            profil organisasi (halaman ini)
└─ (aplikasi produk)        privat            web utama, pusat akun, dan produk lain
```

Kode produk internal bersifat privat karena memuat detail bisnis, katalog, dan konfigurasi. Bagian
yang bisa dipakai ulang oleh siapa saja kami pindahkan ke template publik di atas.

## Prinsip kami

Prinsip ini memandu cara kami membangun dan meninjau kode:

- **Aman dulu.** Tidak ada rahasia di dalam kode. Semua kredensial hidup di environment.
- **Uang ditentukan server.** Harga tidak pernah dipercaya dari halaman atau URL. Akses hanya
  dibuka oleh webhook yang diverifikasi, tidak pernah dari tombol di browser.
- **Data di Indonesia.** Identitas dan tagihan kami simpan sendiri supaya mudah patuh pada UU PDP.
- **Hormati privasi.** Pengguna bisa mengunduh datanya dan menghapus akun.
- **Bisa dipakai semua orang.** Target kontras WCAG AA, fokus keyboard terlihat, dan menghormati
  pengaturan reduce motion.
- **Mobile dulu.** Pengguna kami kebanyakan memakai ponsel, jadi tidak ada aksi penting yang boleh
  tersembunyi.
- **Konten sebagai data.** Tim non-teknis bisa mengubah isi tanpa menunggu rilis.

## Ikut berkontribusi

Kami menyambut isu, ide, dan pull request untuk proyek open-source kami
([account-center-starter](https://github.com/maubisa-id/account-center-starter) dan
[thesisdesk](https://github.com/maubisa-id/thesisdesk)).

1. **Mulai dari repo yang terbuka.** Tiap repo punya `CONTRIBUTING.md` sendiri dengan panduan setup
   dan gate sebelum PR ([account-center-starter](https://github.com/maubisa-id/account-center-starter/blob/main/CONTRIBUTING.md),
   [thesisdesk](https://github.com/maubisa-id/thesisdesk/blob/main/CONTRIBUTING.md)).
2. **Laporkan bug atau minta fitur.** Pakai template issue yang ada di repo terkait.
3. **Kirim perubahan.** Fork, buat branch, lalu buka pull request kecil yang fokus. Sertakan langkah
   uji bila relevan.

Pemula dipersilakan. Kalau ragu mulai dari mana, buka issue dan tanyakan lebih dulu.

## Komunitas dan dukungan

| Kebutuhan | Ke mana |
|-----------|---------|
| Pertanyaan atau bug proyek open-source | Issue di [account-center-starter](https://github.com/maubisa-id/account-center-starter/issues) atau [thesisdesk](https://github.com/maubisa-id/thesisdesk/issues) |
| Bantuan sebagai pengguna produk Maubisa | [maubisa.id](https://maubisa.id) atau halo@maubisa.id |
| Melaporkan celah keamanan (jangan publik) | Kebijakan keamanan repo terkait ([account-center-starter](https://github.com/maubisa-id/account-center-starter/blob/main/SECURITY.md), [thesisdesk](https://github.com/maubisa-id/thesisdesk/blob/main/SECURITY.md)) |
| Aturan berinteraksi | Kode Etik repo terkait ([account-center-starter](https://github.com/maubisa-id/account-center-starter/blob/main/CODE_OF_CONDUCT.md), [thesisdesk](https://github.com/maubisa-id/thesisdesk/blob/main/CODE_OF_CONDUCT.md)) |

> [!IMPORTANT]
> Menemukan celah keamanan pada layanan atau kode kami? Mohon **jangan** membuka issue publik.
> Ikuti kebijakan keamanan di repo dan laporkan secara privat lebih dulu, supaya bisa kami perbaiki
> sebelum diketahui luas.

## Terhubung dengan kami

| Kanal | Tautan |
|-------|--------|
| Situs | [maubisa.id](https://maubisa.id) |
| Pusat akun | [akun.maubisa.id](https://akun.maubisa.id) |
| Demo open source | [demo-akun.maubisa.id](https://demo-akun.maubisa.id) |
| Email umum dan kerja sama | halo@maubisa.id |

<div align="center">
<br/>
<sub>Hak cipta 2026 PT Litera Edu Solusi (Maubisa). Dibuat dengan sungguh-sungguh di Indonesia.</sub>
</div>
