# Kebijakan Keamanan

Keamanan adalah prioritas utama bagi seluruh proyek di Creative Trees, terutama karena banyak
repositori kami menangani data pembayaran, data pengguna, dan sistem operasional yang sensitif.

## Melaporkan Kerentanan

Jika Anda menemukan kerentanan keamanan di salah satu repositori Creative Trees, jangan membuka
issue publik. Laporkan secara privat melalui email ke teamcreativetrees@gmail.com dengan
menyertakan:

- Deskripsi kerentanan dan dampak potensialnya.
- Langkah-langkah untuk mereproduksi masalah tersebut.
- Repositori dan versi/commit yang terpengaruh, bila diketahui.
- Saran perbaikan, apabila ada.

## Apa yang Bisa Anda Harapkan

- Konfirmasi penerimaan laporan dalam waktu 3 hari kerja.
- Penilaian awal tingkat keparahan dalam waktu 7 hari kerja.
- Update berkala mengenai progres penanganan hingga masalah selesai ditangani.
- Kredit atas penemuan (apabila diinginkan) setelah perbaikan dirilis.

## Cakupan

Kebijakan ini berlaku untuk seluruh repositori publik maupun privat di bawah organisasi Creative
Trees, termasuk namun tidak terbatas pada sistem pembayaran, manajemen gudang, ERP/keuangan,
sistem informasi universitas, serta platform donasi dan CMS.

## Praktik Keamanan yang Kami Terapkan

- Validasi input di seluruh endpoint API dan formulir.
- Prinsip least privilege untuk akses database dan layanan pihak ketiga.
- Secret dan kredensial tidak pernah disimpan langsung di kode sumber; gunakan environment variable atau secret manager.
- Dependency diperiksa secara berkala terhadap kerentanan yang diketahui.

Terima kasih telah membantu menjaga ekosistem Creative Trees tetap aman.
