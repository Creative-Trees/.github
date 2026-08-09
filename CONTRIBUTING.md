# Berkontribusi di Creative Trees

Terima kasih atas minat Anda berkontribusi di proyek-proyek Creative Trees! Panduan ini
merangkum alur kerja yang kami pakai di seluruh repositori — dari proyek Laravel/PHP, Svelte,
hingga skrip Python.

## Sebelum mulai

- Baca [Kode Etik](./CODE_OF_CONDUCT.md) — kami mengharapkan semua kontributor mengikutinya.
- Untuk perubahan besar, buka issue terlebih dahulu agar arah pengerjaan disepakati bersama.
- Untuk laporan kerentanan keamanan, jangan buka issue publik — ikuti panduan di SECURITY.md.

## Alur branch & commit

1. Buat branch dari `main` dengan nama deskriptif, misalnya `fix/payment-timeout` atau `feat/dashboard-filter`.
2. Tulis pesan commit yang jelas, idealnya mengikuti gaya Conventional Commits — contoh: `fix: perbaiki validasi nomor rekening`.
3. Jaga setiap commit tetap fokus pada satu perubahan logis agar mudah ditinjau.

## Menyiapkan lingkungan pengembangan

Proyek Creative Trees umumnya memakai salah satu dari stack berikut:

- **Laravel / PHP** — `composer install`, salin `.env.example` ke `.env`, lalu `php artisan migrate`.
- **Svelte** — `npm install` atau `pnpm install`, lalu `npm run dev`.
- **Python** — buat virtual environment, lalu `pip install -r requirements.txt`.

Periksa `README.md` di masing-masing repositori untuk instruksi spesifik proyek tersebut.

## Pull request

- Pastikan kode lulus lint/test yang tersedia di proyek sebelum membuka PR.
- Isi template pull request selengkap mungkin — jelaskan apa yang berubah dan mengapa.
- Tautkan issue terkait bila ada, misalnya `Closes #12`.
- Satu PR sebaiknya membahas satu topik agar peninjauan lebih cepat dan fokus.

## Pelaporan bug & usulan fitur

Gunakan formulir issue yang tersedia (Bug report atau Feature request) agar informasi yang
kami butuhkan untuk menindaklanjuti selalu lengkap sejak awal. Pertanyaan lain? Lihat SUPPORT.md.
