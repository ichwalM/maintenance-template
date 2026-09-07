Anda bertindak sebagai Senior Frontend Engineer sekaligus Motion UI Designer.

Saya ingin Anda membuat SATU halaman website khusus untuk MODE MAINTENANCE website ICLABS.

Gunakan logo ICLABS yang saya lampirkan sebagai referensi visual utama. Logo tersebut berbentuk chip/circuit dengan identitas warna teal/cyan. Jangan mengubah bentuk, proporsi, atau identitas visual logonya.

==================================================
TUJUAN
==================================================

Buat halaman maintenance yang terlihat seperti website teknologi profesional kelas premium, bukan template maintenance biasa.

Konsep utama:

"ICLABS System Maintenance"

Halaman harus memberikan kesan bahwa sistem/infrastruktur digital ICLABS sedang melakukan proses maintenance, diagnostics, optimization, dan reconfiguration.

Visual harus terasa seperti:
- premium technology laboratory
- futuristic
- minimalist
- sophisticated
- professional
- modern university/research technology
- cinematic motion design

JANGAN membuatnya seperti:
- website gaming
- cyberpunk
- hacker interface
- template maintenance generik
- terlalu banyak neon
- terlalu banyak HUD
- terlalu banyak teks
- kartun
- robot/engineer/construction worker

==================================================
TEKNOLOGI
==================================================

Buat project menggunakan:

- HTML5
- CSS3
- Vanilla JavaScript

Gunakan library hanya jika benar-benar memberikan manfaat.

Library yang diperbolehkan:
- GSAP untuk animasi kompleks
- Lucide Icons untuk icon sederhana
- Google Fonts jika diperlukan

Prioritaskan performa.

Tidak perlu framework seperti React, Vue, Next.js, atau Angular.

Halaman harus dapat dijalankan langsung dengan membuka:

index.html

Jika membutuhkan library eksternal, gunakan CDN yang stabil.

==================================================
STRUKTUR FILE
==================================================

Buat struktur sederhana:

/
├── index.html
├── assets/
│   └── iclabs-logo.png
└── README.md

Jika memungkinkan, seluruh styling dan JavaScript dapat berada di index.html agar deployment sangat sederhana.

Jangan membuat dependency yang tidak diperlukan.

==================================================
DESAIN HALAMAN
==================================================

Gunakan full-screen viewport:

100vw × 100vh

Background:
- deep black / charcoal
- sangat subtle gradient
- subtle radial glow di sekitar logo
- tidak boleh terlalu terang

Logo ICLABS berada di tengah sebagai HERO ELEMENT.

Logo harus terlihat besar tetapi tetap memiliki negative space yang cukup.

Tambahkan efek:

1. Soft ambient glow
2. Circuit pulse
3. Data flow
4. Diagnostic scan
5. Node activation/deactivation
6. Subtle particles
7. Very subtle grid
8. Soft light bloom

Semua efek harus elegan dan restrained.

==================================================
ANIMASI UTAMA
==================================================

Buat animasi maintenance yang berjalan secara otomatis dan seamless.

PHASE 1 — SYSTEM ONLINE

Logo ICLABS berada dalam kondisi stabil.

Circuit lines memiliki cahaya cyan/teal yang sangat lembut.

Sesekali ada pulse kecil yang berjalan dari pusat chip menuju circuit nodes.

Durasi sekitar 3 detik.

PHASE 2 — DIAGNOSTIC

Sistem mulai melakukan diagnostic.

Buat scanning light yang bergerak secara perlahan melewati logo.

Beberapa circuit node menyala secara berurutan.

Data pulse bergerak sepanjang circuit.

Durasi sekitar 3 detik.

PHASE 3 — MAINTENANCE MODE

Aktivitas sistem secara perlahan berkurang.

Beberapa circuit node dimatikan secara berurutan.

Logo tetap menyala lembut.

Tambahkan subtle rotating diagnostic ring di sekitar central chip.

Jangan membuat kesan sistem rusak.

Harus terlihat seperti maintenance yang terkontrol.

Durasi sekitar 3 detik.

PHASE 4 — OPTIMIZATION

Partikel dan energy pulse bergerak kembali menuju central chip.

Circuit nodes aktif kembali satu per satu.

Pulse cyan menyebar dari central chip menuju seluruh circuit.

Durasi sekitar 3 detik.

PHASE 5 — SYSTEM RESTORED

Semua circuit kembali aktif.

Logo mencapai kondisi paling stabil.

Lakukan satu elegant final pulse melewati seluruh circuit.

Kemudian transisi kembali secara seamless ke PHASE 1.

Total loop sekitar 12–15 detik.

==================================================
TEKS
==================================================

Gunakan teks yang sangat minimal.

Di bawah logo:

SYSTEM MAINTENANCE

Kemudian:

ICLABS is currently undergoing scheduled maintenance.
We'll be back shortly.

Tambahkan status kecil:

● SYSTEM MAINTENANCE IN PROGRESS

Gunakan typography modern dan profesional.

Jangan menggunakan kalimat panjang.

Jangan membuat paragraf besar.

==================================================
INTERAKSI
==================================================

Tambahkan tombol:

"Back to Home"

Tombol harus minimalis.

Normal state:
- transparent / glass
- subtle border
- teal accent

Hover:
- subtle glow
- smooth transition
- sedikit perubahan background

Jangan menggunakan efek berlebihan.

==================================================
RESPONSIVE
==================================================

WAJIB responsive.

Desktop:
- hero logo besar
- layout centered

Tablet:
- ukuran logo menyesuaikan

Mobile:
- logo mengecil secara proporsional
- typography mengecil
- tidak boleh terjadi horizontal scrolling
- semua elemen tetap berada di tengah
- tombol mudah disentuh

Pastikan halaman terlihat bagus pada:
- 1920×1080
- 1440×900
- 1366×768
- 1024×768
- 768×1024
- 390×844
- 360×800

==================================================
PERFORMANCE
==================================================

Ini adalah halaman maintenance yang kemungkinan akan menjadi halaman sementara, sehingga harus sangat ringan.

WAJIB:

- optimize rendering
- hindari animasi yang menyebabkan CPU/GPU usage tinggi
- gunakan transform dan opacity untuk animasi jika memungkinkan
- jangan gunakan canvas dengan particle berlebihan
- jangan membuat ratusan DOM elements
- gunakan prefers-reduced-motion
- jika user mengaktifkan reduced motion, matikan animasi kompleks
- jangan menggunakan video background yang berat
- jangan menggunakan image besar yang tidak diperlukan

Gunakan GPU-friendly animation.

==================================================
ACCESSIBILITY
==================================================

Implementasikan:

- semantic HTML
- proper heading hierarchy
- accessible button
- aria-label jika diperlukan
- sufficient contrast
- keyboard navigation
- prefers-reduced-motion

==================================================
LOGO
==================================================

Gunakan file logo ICLABS yang saya berikan.

Jangan menggambar ulang logo menggunakan SVG baru jika file logo sudah dapat digunakan.

Pertahankan:
- bentuk
- warna
- proporsi
- identitas
- circuit structure

Logo harus menjadi focal point utama halaman.

Jika file logo memiliki background transparan, pertahankan transparansinya.

==================================================
VISUAL HIERARCHY
==================================================

Prioritas visual:

1. ICLABS logo
2. maintenance animation
3. "SYSTEM MAINTENANCE"
4. description
5. status indicator
6. Back to Home

Jangan membuat teks lebih dominan daripada logo.

==================================================
MICRO INTERACTIONS
==================================================

Tambahkan micro-interaction kecil:

- status indicator breathing/pulsing
- logo subtle breathing glow
- button hover
- circuit data pulses
- node activation
- diagnostic scan

Semua harus terasa halus dan premium.

==================================================
BACKGROUND
==================================================

Buat background yang sangat subtle.

Contoh:

deep charcoal background
+
radial teal glow di sekitar logo
+
very subtle technical grid
+
minimal floating particles

Grid dan particles jangan sampai mengganggu logo.

==================================================
CODE QUALITY
==================================================

Tulis kode production-quality.

Gunakan:
- CSS variables
- clean class naming
- modular JavaScript functions
- comments hanya pada bagian penting
- tidak ada dead code
- tidak ada console error
- tidak ada library yang tidak digunakan
- tidak ada placeholder yang tidak diperlukan

Pastikan:

index.html

dapat langsung dibuka dan halaman langsung berjalan.

==================================================
SEO / META
==================================================

Tambahkan:

- title
- meta description
- viewport
- theme-color
- favicon jika logo dapat digunakan sebagai favicon

Title:

ICLABS — System Maintenance

Description:

ICLABS is currently undergoing scheduled system maintenance. We'll be back shortly.

==================================================
HASIL AKHIR
==================================================

Saya tidak ingin sekadar mendapatkan mockup.

Buat halaman yang benar-benar siap digunakan sebagai production maintenance page.

Pastikan hasil akhirnya terasa seperti:

"sebuah research/technology laboratory modern yang sedang melakukan maintenance terhadap infrastruktur digitalnya"

bukan:

"website sedang rusak."

Fokus utama adalah:
PREMIUM + MINIMALIST + FUTURISTIC + PROFESSIONAL + SMOOTH MOTION.

Setelah selesai:

1. Buat seluruh file yang diperlukan.
2. Pastikan index.html dapat langsung dijalankan.
3. Pastikan logo ICLABS digunakan.
4. Pastikan animasi seamless.
5. Pastikan responsive.
6. Pastikan tidak ada console error.
7. Pastikan performa ringan.
8. Sertakan README.md yang menjelaskan cara menjalankan dan melakukan deployment.
9. Jika menggunakan CDN/library, jelaskan library tersebut di README.
10. Jangan menambahkan fitur yang tidak berhubungan dengan maintenance page.

JANGAN bertanya kembali jika requirement di atas sudah cukup jelas. Langsung implementasikan.