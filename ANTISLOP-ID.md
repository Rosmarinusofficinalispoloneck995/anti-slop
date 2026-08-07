# Anti AI Slop: Design & Copy Rules

> Panduan ini wajib diikuti ketika menghasilkan atau membuat tampilan desain website, web app, atau antarmuka apapun.
> Tujuannya: desain terasa **dirancang oleh desainer**, bukan di-generate oleh AI.

---

## Apa Ini (dan Bukan Apa Ini)

`ANTISLOP.md` adalah **filter**, bukan style guide. Ia menghentikan AI coding agent untuk menghasilkan UI "AI slop" yang generik dan mudah dikenali.

- Dokumen ini **tidak** memaksakan aesthetic: tidak ada warna, font, layout, atau "house style" yang ditetapkan.
- Preferensi desain, arah brand, dan selera visual tetap milik kamu.
- Dokumen ini hanya melakukan dua hal:
  1. Mendaftar pola generik AI yang harus dihindari.
  2. Menahan hasil pada standar craftsmanship: intentional, fungsional, lengkap, berbasis bukti.

## Prinsip Utama

Setiap keputusan visual harus memiliki **alasan yang jelas**, meningkatkan pengalaman pengguna, dan membangun identitas produk yang unik.

Pertanyaan yang harus selalu dijawab sebelum menyatakan selesai:

> Jika logo dan nama produk diganti, apakah desain ini masih terasa unik dan memiliki karakter?

Jika jawabannya **tidak**, berarti desain terlalu generik. Ulangi.

Suatu desain **selesai** hanya ketika ketiganya benar:
1. Bebas dari pola slop dalam dokumen ini.
2. Memiliki identitas dan karakter sendiri.
3. Benar-benar berfungsi (lihat Standar Craftsmanship).

## Standar Craftsmanship

"Bukan slop" adalah batas bawah, bukan tujuan. Sebuah desain lulus ketika memenuhi lima kriteria yang netral terhadap selera. Gunakan ini sebagai pertanyaan, bukan resep.

### C-1 — Intentionalitas

Setiap keputusan visual dan copy punya alasan yang bisa kamu jelaskan. Jika satu-satunya alasan adalah "itu default AI", itu red flag: tinjau ulang keputusan tersebut.

### C-2 — Kelengkapan Fungsional

Setiap elemen interaktif berfungsi, atau tidak ada. Tombol yang tidak bisa melakukan apa pun adalah cacat, bukan dekorasi.

### C-3 — Komposisi Berbasis Konten

Setiap section ada karena konten produk membutuhkannya, bukan karena semua landing page AI memilikinya. Hapus section yang hanya mengisi template.

### C-4 — Ketahanan

UI tetap kokoh di setiap state (kosong, memuat, error), setiap tema yang kamu kirim, setiap breakpoint, dan penggunaan hanya dengan keyboard.

### C-5 — Bukti di Atas Klaim

Apa pun yang disajikan sebagai fakta (testimonial, statistik, klaim keamanan) harus nyata dan bisa diverifikasi, atau tidak ditampilkan sama sekali.

---

## Bagian 1: Ciri-Ciri AI Slop (Kenali & Hindari)

Berikut adalah pola-pola yang paling sering muncul pada desain hasil AI. Gunakan sebagai referensi. **Semakin banyak ciri berikut muncul bersamaan, semakin besar kemungkinan desain menjadi AI slop.** Tidak ada angka pasti; konteks dan alasan di balik setiap pilihan yang menentukan.

### Visual & Warna

| Pola | Ciri Khas |
|------|-----------|
| **Gradient Biru-Ungu Generik** | Biru ke Ungu, Biru ke Cyan, Ungu ke Pink, background penuh glow berwarna |
| **Glassmorphism Berlebihan** | Blur di navbar, card, modal, sidebar semuanya |
| **Border Radius Berlebihan** | Semua elemen berbentuk pil: button, input, card, badge, modal |
| **Shadow Terlalu Lembut** | Semua komponen punya shadow besar, seluruh halaman terasa melayang |
| **Glow Dimana-Mana** | Glow pada card, tombol, icon, badge, background, border secara bersamaan |
| **Background Grid** | Kotak-kotak, blueprint, graph paper, garis tipis horizontal-vertikal |
| **Terlalu Banyak Dekorasi / Menumpuk Tren** | Blob, mesh gradient, glow, noise, pattern, grid tanpa fungsi, apalagi jika beberapa tren dipakai sekaligus (mis. Glassmorphism + Mesh Gradient + Glow + Monospace + Grid + Rounded UI) |
| **Dark Mode Default Tanpa Alasan** | Seluruh halaman gelap hanya karena terlihat "tech", tanpa pertimbangan branding |
| **Terlalu Banyak Warna dalam Palette** | Memakai 5-7 warna berbeda dalam satu halaman tanpa design system yang jelas |
| **Warna Aksen Berlebihan** | Satu warna aksen di tombol, icon, badge, link, garis, background, glow |

### Layout & Komponen

| Pola | Ciri Khas |
|------|-----------|
| **Layout Monoton** | Hero, Subtitle, 2 CTA, Screenshot, Grid Fitur, Testimonial, FAQ, CTA, Footer |
| **Feature Card Copy-Paste** | Ukuran, tinggi, icon, layout, padding semua sama persis |
| **Spacing Seragam** | Padding, margin, jarak antar elemen identik di semua section |
| **Mobile Berantakan** | Overflow horizontal, card keluar layar, navbar rusak, teks bertabrakan |
| **Animasi Template** | Semua elemen pakai Fade Up, Fade In, Floating, Scale, Bounce |
| **"How It Works" 3 Langkah** | Icon bulat + angka 1, 2, 3 + teks pendek, selalu tiga langkah, selalu sama |
| **"Trusted By" Logo Bar** | Deretan logo perusahaan generik langsung di bawah hero |
| **Pricing Card "Most Popular"** | Tier tengah selalu di-highlight dengan badge kapsul |
| **Footer 4 Kolom Template** | Kolom Product / Company / Resources / Legal tanpa variasi |

### Copywriting & Konten

| Pola | Ciri Khas |
|------|-----------|
| **Em Dash (—)** | "Fast, secure — and built for developers." |
| **CTA Generik** | Get Started, Learn More, Try Now, Explore, Discover |
| **Buzzword Marketing AI** | AI Powered, Revolutionary, Next Generation, Seamless, Cutting Edge |
| **Statistik Palsu** | 10K+ Users, 99.9% Uptime, 500M Requests, 120+ Countries |
| **Testimonial Palsu** | Avatar AI, nama acak, jabatan acak, review fiktif |
| **Klaim Kepercayaan Karangan** | "SOC 2 compliant", "ISO 27001", "Enterprise-grade security", "300% faster" untuk produk yang tidak punya bukti apa pun |

### Elemen Dekoratif

| Pola | Ciri Khas |
|------|-----------|
| **Ikon AI Generik** | Sparkle, Star, Magic, Lightning, Diamond, Cube, Robot, Orb AI |
| **Arrow Kecil (→ / ↗)** | Dipasang di hampir semua tombol sebagai dekorasi |
| **Badge Kapsul AI** | Bentuk pil, border tipis, glow, titik kecil, uppercase, berisi: "AI Powered", "Beta", "New" |
| **Typography AI Generik** | Heading monospace besar, label HOW IT WORKS uppercase tracking lebar |
| **Typeface Dipilih Tanpa Alasan** | Memilih font karena default AI, bukan karena sesuai karakter brand. Font populer seperti Inter tetap valid jika ada alasannya |
| **Ilustrasi Generik** | Ilustrasi Undraw, Storyset, atau karakter blob 3D tanpa hubungan nyata dengan produk |

### Fungsionalitas & Konten

| Pola | Ciri Khas |
|------|-----------|
| **Elemen Interaktif Tidak Berfungsi** | Tombol tidak melakukan apa pun, dropdown tidak terbuka, form tidak bisa disubmit. AI bikin tampilan tapi lupa bikin fungsinya |
| **Desain Hanya untuk Happy Path** | Tidak ada empty state, loading state, atau error state. UI terlihat sempurna di screenshot tapi tidak siap dipakai nyata |
| **FAQ Tidak Relevan** | Pertanyaan FAQ berisi template generik ("Is my data secure?", "Can I cancel anytime?") tanpa relevansi nyata dengan produk |
| **Logo & Foto Profil Asal Bikin** | Membuat logo aplikasi, avatar, atau foto profil tanpa instruksi eksplisit, asal generate berdasarkan asumsi |
| **Navbar Link Tanpa Konten** | Navbar berisi link ke halaman (Features, Contact, About, dll.) yang tidak ada section atau halamannya sama sekali |
| **Patching File/CSS via Script** | Fitur (mis. dark mode) ditambahkan oleh script eksternal yang menulis ulang source atau CSS dengan string replacement. Tanda: helper `.py`/`.js` yang melakukan `str.replace` pada file `.css`, script "patch" yang tertinggal di repo |

### Identitas & Orisinalitas

| Pola | Ciri Khas |
|------|-----------|
| **Tanpa Identitas Visual** | Ganti logo, desain tetap terasa sama, bisa dipakai produk apa pun |
| **Clone Produk Populer** | Tampilan yang secara keseluruhan meniru Linear, Vercel, Stripe, Notion, atau produk populer lain tanpa diminta |

### Aksesibilitas

| Pola | Ciri Khas |
|------|-----------|
| **Color Contrast Buruk** | Teks abu-abu di background abu-abu, teks putih di gradient yang terang di sebagian area. Terlihat oke secara visual tapi gagal WCAG |
| **Tidak Bisa Dinavigasi Keyboard** | UI hanya bisa dipakai dengan mouse. Elemen interaktif tidak bisa dijangkau dengan Tab, tidak ada focus state yang terlihat |

---

## Bagian 2: Rules Wajib Diikuti

### R-01 — Warna & Gradien

- **DILARANG**: gradient biru ke ungu, biru ke cyan, ungu ke pink sebagai warna utama
- **DILARANG**: background glow berwarna sebagai default
- **DILARANG**: tombol biru neon tanpa alasan branding
- Gradien **boleh** dipakai jika memang bagian dari branding yang sudah ditentukan, bukan sebagai pilihan default

### R-02 — Copywriting

- **DILARANG**: karakter em dash (`—`) dalam teks apapun
- Gunakan koma (`,`), titik (`.`), titik dua (`:`), atau tanda kurung `()`
- Teks harus terasa natural dan manusiawi

### R-03 — Responsivitas Mobile

- **WAJIB**: tampilan mobile harus sempurna, bukan afterthought
- Tidak ada overflow horizontal
- Teks tidak keluar container
- Card tidak bertabrakan atau keluar layar
- Navbar tetap nyaman digunakan
- Ukuran tombol memenuhi minimum tap target (44px)
- Spacing tetap konsisten di semua breakpoint
- **Responsive adalah bagian dari desain, bukan tambahan.**

### R-04 — Ikon

- **DILARANG**: Sparkle, Star, Magic, Lightning, Diamond, Orb, Robot sebagai ikon fitur
- Ikon harus **benar-benar relevan** dengan isi konten yang diwakilinya
- Jika tidak ada ikon yang tepat, lebih baik tidak pakai ikon

### R-05 — Layout & Struktur Halaman

- **DILARANG**: layout template AI (Hero + 3 card, Hero + 6 feature, Hero + statistik palsu, dst.)
- **DILARANG**: "How It Works" selalu 3 langkah dengan icon bulat dan angka
- **DILARANG**: "Trusted By" logo bar generik langsung di bawah hero
- **DILARANG**: footer 4 kolom template Product / Company / Resources / Legal tanpa variasi
- Setiap halaman harus memiliki struktur yang dibuat berdasarkan **kebutuhan konten nyata**
- Urutan section harus mengikuti alur narasi produk, bukan urutan default AI (lihat Standar Craftsmanship C-3)

### R-06 — Typography

- **DILARANG**: font monospace besar hanya untuk estetika "terminal"
- **DILARANG**: label uppercase dengan letter-spacing ekstrem (`HOW IT WORKS`, `FEATURES`) tanpa alasan desain
- Pilih typeface berdasarkan karakter brand, bukan karena merupakan pilihan default model AI
- Typography harus **meningkatkan keterbacaan** dan mencerminkan karakter produk

### R-07 — Background

- **DILARANG**: grid kotak-kotak, blueprint, graph paper sebagai background default
- Gunakan texture atau pola hanya jika memang mendukung identitas visual produk secara spesifik

### R-08 — Arrow pada Tombol

- Arrow (`→`, `↗`) bukan identitas default semua tombol
- Jika dipakai, pastikan ukurannya proporsional dan memiliki fungsi visual yang jelas
- Tidak semua CTA perlu arrow

### R-09 — Badge

- **DILARANG**: badge kapsul berisi "AI Powered", "Beta", "New", "Secure", "Fast" tanpa konteks
- Badge hanya boleh dipakai jika **dibutuhkan secara fungsional**
- Hindari kombinasi: kapsul + border tipis + glow + titik kecil + uppercase sekaligus

### R-10 — Glassmorphism

- Glassmorphism hanya sebagai **aksen**, bukan karakter seluruh UI
- **DILARANG**: blur/backdrop-filter di navbar, card, modal, sidebar secara bersamaan
- Pilih maksimal 1-2 elemen yang mendapat treatment glass

### R-11 — Border Radius

- Gunakan border radius yang **konsisten sesuai design system yang ditentukan**
- **DILARANG**: semua elemen dibuat pil (tombol pil, card pil, input pil, badge pil)
- Variasi radius adalah alat hierarchy visual, gunakan dengan sengaja

### R-12 — Shadow

- Shadow harus membantu **hierarchy visual**, bukan membuat semua elemen melayang
- Gunakan shadow secara selektif, bukan sebagai default semua komponen
- Pertimbangkan shadow sebagai penanda elevation, bukan dekorasi

### R-13 — Glow

- Glow hanya boleh digunakan sebagai **aksen fokus** pada maksimal 1-2 elemen penting
- **DILARANG**: glow pada card + button + badge + icon + background + border secara bersamaan

### R-14 — Feature Card

- **DILARANG**: semua card dengan ukuran, ikon, padding, dan layout yang identik
- Buat variasi visual yang mencerminkan hierarchy konten
- Tidak semua fitur perlu dipresentasikan dengan card

### R-15 — CTA (Call to Action)

- **DILARANG**: "Get Started", "Learn More", "Try Now", "Explore", "Discover" sebagai CTA default
- CTA harus **spesifik sesuai konteks produk dan aksi yang diinginkan**
- Contoh yang lebih baik: "Coba 14 Hari Gratis", "Lihat Demo Langsung", "Buat Akun Gratis"

### R-16 — Copywriting & Buzzword

- **DILARANG**: "AI Powered", "Next Generation", "Revolutionary", "Seamless", "Cutting Edge", "Intelligent", "Ultimate", "Powerful", "Effortless"
- Gunakan bahasa **spesifik** yang menjelaskan manfaat nyata
- Tunjukkan bukti, bukan klaim

### R-17 — Data & Angka

- **DILARANG**: angka dan statistik yang tidak memiliki sumber nyata
- Jika data asli tidak tersedia, jangan tampilkan angka apapun
- Lebih baik kosong daripada menipu

### R-18 — Testimonial

- **DILARANG**: avatar AI, nama acak, jabatan acak, review fiktif
- Jika tidak memiliki testimonial asli, jangan buat section testimonial
- Gunakan social proof yang bisa diverifikasi

### R-19 — Animasi

- Animasi harus memiliki **tujuan UX yang jelas**
- **DILARANG**: semua elemen menggunakan Fade Up + Floating + Scale + Bounce sekaligus
- Animasi yang berlebihan adalah gangguan, bukan nilai tambah
- Gunakan animasi untuk memandu perhatian, bukan sekadar mengisi halaman

### R-20 — Identitas Visual

- Desain harus memiliki identitas yang kuat: palette spesifik, typeface yang dipilih dengan alasan, komposisi yang unik
- Setiap section harus memiliki hierarchy yang jelas
- Layout dibuat berdasarkan kebutuhan konten produk
- Identitas berasal dari pilihan yang disengaja dan dijelaskan, bukan dari menambah dekorasi (lihat Standar Craftsmanship C-1)

### R-21 — Dark Mode

- Pilih tema berdasarkan identitas brand, jenis produk, dan target pengguna
- Developer tools, terminal, dan creative tools punya alasan kuat dan sah untuk dark default. Gunakan alasan itu, bukan "dark terlihat tech"
- Jika produk tidak punya alasan kuat untuk tema tetap, **bangun toggle light/dark yang berfungsi**. "Beri user pilihan" berarti bangun toggle-nya, bukan menunda pekerjaan
- **DILARANG**: menggunakan rule ini (atau rule apapun) sebagai alasan untuk melewati atau menunda pekerjaan yang diminta. Jika produk seharusnya mendukung dark mode, implementasikan sekarang
- Theme toggle yang kamu kirim harus bekerja benar di KEDUA mode. Dark mode yang merusak light mode adalah cacat (lihat R-34)

### R-22 — Ilustrasi

- **DILARANG**: ilustrasi Undraw, Storyset, atau karakter blob 3D generik
- Ilustrasi harus memiliki hubungan langsung dengan produk atau konten yang disajikan
- Jika tidak ada ilustrasi yang tepat dan original, gunakan screenshot nyata atau tidak pakai ilustrasi sama sekali

### R-23 — Klarifikasi & Aset Visual

- **WAJIB**: sebelum membuat aset yang tidak ada instruksinya, tanya atau gunakan placeholder yang jelas
- Jika ada kesempatan bertanya, konfirmasi dulu hal-hal berikut:
  - Logo atau ikon aplikasi (bentuk, warna, konsep)
  - Avatar, foto profil, atau gambar representasi orang/tim
  - Statistik dan angka yang akan ditampilkan
  - Nama, jabatan, atau identitas dalam testimonial
  - Navigasi dan struktur halaman yang diinginkan
- Jika tidak bisa bertanya (prototyping cepat, konteks terbatas): gunakan placeholder yang jelas dan jangan samarkan sebagai final
  - Logo: teks nama produk dalam typeface sesuai, atau tanda `[LOGO]`
  - Foto profil: initial-based avatar atau placeholder geometris sederhana
  - Statistik: tidak ditampilkan, atau ditandai `[DATA ASLI]`
- **Jangan pernah generate aset seolah-olah itu adalah versi final tanpa konfirmasi**
- Jika sudah ada instruksi yang jelas, langsung generate tanpa tanya ulang

### R-24 — Navigasi

- **DILARANG**: menaruh link di navbar untuk halaman atau section yang tidak ada dalam desain
- Setiap item navigasi harus memiliki destination yang nyata dan bisa diakses
- Jika ada fitur yang belum dibuat, jangan masukkan ke navbar, atau beri keterangan jelas bahwa itu coming soon
- Navbar harus mencerminkan struktur konten yang benar-benar ada

### R-25 — Color Contrast

- **WAJIB**: semua teks harus memenuhi standar kontras minimum WCAG AA
  - Teks normal: rasio kontras minimal 4.5:1
  - Teks besar (18px+): rasio kontras minimal 3:1
- **DILARANG**: teks abu-abu muda di background abu-abu
- **DILARANG**: teks putih di area gradient yang sebagian bagiannya terang
- Selalu uji kontras di seluruh area yang dilewati teks, bukan hanya di satu titik

### R-26 — Elemen Interaktif

Setiap elemen interaktif harus memiliki perilaku nyata, atau dihapus:

- Link atau tombol yang scroll ke section yang benar-benar ada (real `href="#..."`)
- Modal atau dialog yang terbuka dan tertutup (bisa ditutup dengan Escape)
- State toggle (menu mobile, tema, accordion, tabs)
- Aksi eksternal (`mailto:`, URL produk yang nyata)
- Form yang submit dan menampilkan feedback

**DILARANG**: tombol dan link yang tidak melakukan apa pun
**DILARANG**: item nav yang mengarah ke section yang tidak ada (lihat R-24)

Jika sebuah elemen benar-benar belum punya destination, hapus elemen tersebut daripada mengirim kontrol mati. Placeholder hanya diperbolehkan dengan komentar `// TODO` yang jelas di kode DAN label yang terlihat oleh user (mis. "Coming soon"). Lihat "Pola Fungsional" di bawah.

### R-27 — UI States

- **WAJIB**: setiap UI yang menampilkan data harus memiliki setidaknya tiga state:
  - **Empty state**: tampilan ketika belum ada data
  - **Loading state**: indikator saat data sedang dimuat
  - **Error state**: tampilan ketika terjadi kesalahan
- UI yang hanya didesain untuk kondisi ideal tidak siap dipakai nyata
- State ini bukan bonus, ini bagian dari desain yang lengkap

### R-28 — FAQ

- **DILARANG**: FAQ berisi pertanyaan template yang tidak spesifik terhadap produk
- Setiap pertanyaan dalam FAQ harus menjawab kekhawatiran nyata pengguna produk tersebut
- Jika tidak tahu pertanyaan nyata yang sering diajukan, jangan buat section FAQ
- FAQ yang generik lebih merusak kepercayaan daripada tidak ada FAQ sama sekali

### R-29 — Palette Warna

- **WAJIB**: batasi palette aktif maksimal 2-3 warna inti + 1 warna aksen
- **DILARANG**: menggunakan 5+ warna berbeda dalam satu halaman tanpa design system yang jelas
- Warna netral (white, black, grey) tidak dihitung sebagai bagian dari palette inti
- Konsistensi palette adalah fondasi identitas visual yang kuat

### R-30 — Jangan Meniru Produk Populer

- **DILARANG**: membuat tampilan yang secara keseluruhan meniru produk lain tanpa diminta
  - "Buat tampilan seperti Linear" (kecuali user memang memintanya)
  - "Buat tampilan seperti Vercel" (kecuali user memang memintanya)
  - "Buat tampilan seperti Stripe / Notion / Apple" (kecuali user memang memintanya)
- AI cenderung default ke clone produk populer karena pola tersebut mendominasi data training
- Referensi visual boleh dipakai sebagai inspirasi, bukan sebagai template yang disalin
- Produk harus memiliki identitas visualnya sendiri, bukan identitas produk lain

### R-31 — Setiap Keputusan Harus Memiliki Alasan

Sebelum menyelesaikan desain, pastikan ada jawaban yang jelas untuk setiap keputusan utama:

- Mengapa memakai warna tersebut?
- Mengapa memilih layout tersebut?
- Mengapa memakai typography tersebut?
- Mengapa memakai spacing tersebut?
- Mengapa menggunakan card?
- Mengapa memakai ilustrasi atau ikon?

Jika tidak ada alasan yang bisa dijelaskan, keputusan tersebut belum valid dan harus ditinjau ulang. Rule ini mengubah AI dari sekadar "menghasilkan UI" menjadi "merancang UI".

### R-32 — Aksesibilitas Keyboard

- **WAJIB**: semua elemen interaktif harus bisa dijangkau dan dioperasikan dengan keyboard
  - Navigasi dengan `Tab` dan `Shift+Tab` harus bekerja secara logis mengikuti urutan visual
  - Tombol dan link harus bisa diaktifkan dengan `Enter` atau `Space`
  - Dialog dan modal harus bisa ditutup dengan `Escape`
- **WAJIB**: setiap elemen yang sedang difokus harus memiliki focus indicator yang terlihat jelas
- **DILARANG**: menghilangkan outline focus dengan `outline: none` atau `outline: 0` tanpa menggantinya dengan indikator fokus custom yang lebih baik
- UI yang hanya bisa dipakai dengan mouse adalah UI yang belum selesai

### R-33 — Dilarang Patching File/CSS via Script

- **DILARANG**: mengimplementasikan atau mengubah fitur UI dengan menjalankan script eksternal yang menulis ulang source file atau CSS dengan string replacement
- Bangun fitur langsung di source code tempatnya berada
- Fitur yang ditambahkan oleh patch script (mis. script Python yang mengedit file `.css`) rusak sejak awal dan harus ditulis ulang di source

### R-34 — Setiap Tema yang Dikirim Harus Berfungsi

- Jika kamu mengirim theme toggle, KEDUA mode harus berfungsi penuh
- Kontras, warna, dan setiap komponen harus diverifikasi di masing-masing mode
- **DILARANG**: mengirim mode di mana base styles, font, atau layout rusak

### R-35 — Verifikasi Sebelum Menyerahkan

- Jalankan atau build app sebelum menyatakan tugas selesai
- Cek console untuk error
- Uji setiap elemen interaktif
- Cek setiap tema dan breakpoint mobile
- Desain yang tidak pernah dijalankan adalah desain yang belum selesai

### R-36 — Dilarang Klaim Karangan

- **DILARANG**: mengarang klaim keamanan, kepatuhan, atau performa ("SOC 2 compliant", "ISO 27001", "300% faster") tanpa bukti nyata
- **DILARANG**: testimonial palsu, statistik palsu, nama palsu (lihat R-17, R-18)
- Jika tidak ada data nyata, jangan tampilkan klaim apa pun

---

## Pola Fungsional

"Apa yang dimaksud berfungsi" berarti salah satu dari ini, tergantung konteks:

- **Anchor ke section yang nyata**: `href="#pricing"` di mana `#pricing` benar-benar ada
- **Scroll ke konten yang relevan** untuk link gaya "Learn more"
- **Buka modal atau dialog** untuk aksi cepat (bisa ditutup dengan Escape)
- **Toggle state**: menu mobile, tema, accordion, tabs
- **Aksi eksternal**: `mailto:`, URL produk yang nyata
- **Submit form** dengan feedback yang terlihat

Jika tidak ada satu pun yang berlaku untuk sebuah elemen, elemen itu seharusnya tidak ada.

---

## Delivery Gate (Wajib)

Jalankan gate ini SEBELUM menyerahkan. Sertakan statusnya bersama hasil kirimanmu.
Jika salah satu jawaban **ya**, jangan serahkan: perbaiki dulu, lalu jalankan ulang.

### Standar Craftsmanship

- [ ] C-1: Apakah ada keputusan visual atau copy yang satu-satunya pembenarannya adalah "itu default AI"? *(Intentionalitas)*
- [ ] C-2: Apakah ada elemen interaktif yang tidak melakukan apa pun tanpa label yang jelas? *(Kelengkapan Fungsional)*
- [ ] C-3: Apakah ada section yang hanya ada untuk mengisi template AI, bukan melayani konten produk? *(Komposisi Berbasis Konten)*
- [ ] C-4: Apakah UI rusak di state, tema, breakpoint mana pun, atau tanpa mouse? *(Ketahanan)*
- [ ] C-5: Apakah ada testimonial, statistik, atau klaim yang dikarang? *(Bukti di Atas Klaim)*

### Checklist Rules

Sebelum menyatakan desain selesai, jawab semua pertanyaan di bawah ini. Semua jawaban harus **tidak**:

- [ ] Apakah ada gradient biru-ungu/biru-cyan/ungu-pink, background glow berwarna, atau tombol biru neon sebagai default tanpa alasan branding? *(R-01)*
- [ ] Apakah ada em dash (`—`) dalam teks? *(R-02)*
- [ ] Apakah ada overflow horizontal, teks keluar container, atau layout rusak di mobile? *(R-03)*
- [ ] Apakah ada ikon generik (sparkle, star, magic, lightning, diamond, robot, orb) atau ikon yang tidak relevan dengan kontennya? *(R-04)*
- [ ] Apakah layout mengikuti template AI: Hero+card generik, "How It Works" selalu 3 langkah, "Trusted By" logo bar, atau footer 4 kolom tanpa variasi? *(R-05)*
- [ ] Apakah ada font monospace besar, label uppercase tracking lebar, atau typeface yang dipilih tanpa alasan karakter brand? *(R-06)*
- [ ] Apakah ada background grid, blueprint, atau graph paper tanpa fungsi identitas visual? *(R-07)*
- [ ] Apakah arrow (`→` / `↗`) dipasang di hampir semua tombol sekadar sebagai dekorasi? *(R-08)*
- [ ] Apakah ada badge kapsul ("AI Powered", "Beta", "New", "Secure", "Fast") tanpa fungsi nyata, atau kombinasi kapsul + border tipis + glow + uppercase sekaligus? *(R-09)*
- [ ] Apakah glassmorphism dipakai di lebih dari 1-2 elemen sekaligus (navbar + card + modal + sidebar)? *(R-10)*
- [ ] Apakah semua elemen (button, card, input, badge) dibuat berbentuk pil tanpa variasi radius? *(R-11)*
- [ ] Apakah shadow besar dipakai di semua komponen sehingga halaman terasa melayang? *(R-12)*
- [ ] Apakah glow dipakai di card, button, badge, icon, background, dan border secara bersamaan? *(R-13)*
- [ ] Apakah semua feature card punya ukuran, ikon, padding, dan layout yang identik? *(R-14)*
- [ ] Apakah CTA masih generik (Get Started, Learn More, Try Now, Explore, Discover)? *(R-15)*
- [ ] Apakah ada buzzword marketing AI (AI Powered, Seamless, Revolutionary, Cutting Edge, dll.)? *(R-16)*
- [ ] Apakah ada statistik yang tidak memiliki sumber nyata (10K+ Users, 99.9% Uptime, dll.)? *(R-17)*
- [ ] Apakah ada testimonial fiktif (avatar AI, nama atau jabatan acak)? *(R-18)*
- [ ] Apakah semua elemen memakai animasi template yang sama sekaligus (Fade Up + Floating + Scale + Bounce) tanpa tujuan UX yang jelas? *(R-19)*
- [ ] Apakah desain masih terasa generik meski logo dan nama produk diganti? *(R-20)*
- [ ] Apakah dark mode dipaksa sebagai default tanpa alasan branding/user, atau toggle light/dark yang dibutuhkan ditunda dengan alasan? *(R-21)*
- [ ] Apakah ada ilustrasi generik (Undraw, Storyset, blob 3D) tanpa hubungan nyata dengan produk? *(R-22)*
- [ ] Apakah ada aset visual (logo, avatar/foto profil, statistik, testimonial, atau struktur navigasi) yang dibuat tanpa instruksi eksplisit atau konfirmasi? *(R-23)*
- [ ] Apakah ada navbar link yang mengarah ke section atau halaman yang tidak ada? *(R-24)*
- [ ] Apakah ada teks dengan kontras di bawah standar WCAG AA (4.5:1 teks normal, 3:1 teks besar)? *(R-25)*
- [ ] Apakah ada tombol, dropdown, atau form yang tidak melakukan apa pun, tanpa perilaku nyata dan tanpa `// TODO` + label yang terlihat? *(R-26)*
- [ ] Apakah UI tidak punya empty state, loading state, atau error state? *(R-27)*
- [ ] Apakah FAQ berisi pertanyaan generik yang tidak relevan dengan produk? *(R-28)*
- [ ] Apakah palette warna melebihi 2-3 warna inti + 1 aksen tanpa design system yang jelas? *(R-29)*
- [ ] Apakah desain secara keseluruhan terlihat seperti clone dari produk populer lain (Linear, Vercel, Stripe, Notion, dll.)? *(R-30)*
- [ ] Apakah ada keputusan desain (warna, layout, typography, spacing, card, ilustrasi/ikon) yang tidak bisa dijelaskan alasannya? *(R-31)*
- [ ] Apakah UI tidak bisa dinavigasi dengan keyboard (Tab, Enter, Escape) atau tidak ada focus state yang terlihat? *(R-32)*
- [ ] Apakah ada fitur yang ditambahkan dengan patching source/CSS via script eksternal, bukan ditulis langsung di source? *(R-33)*
- [ ] Jika ada theme toggle, apakah salah satu mode (light atau dark) merusak styles, font, atau layout? *(R-34)*
- [ ] Apakah app dijalankan/di-build dan setiap elemen interaktif diuji sebelum diserahkan? *(R-35)*
- [ ] Apakah ada klaim keamanan, kepatuhan, performa, atau pelanggan yang dikarang? *(R-36)*

Jika satu saja jawaban **ya**, jangan serahkan. Perbaiki, jalankan ulang gate, dan baru kemudian kirim. Penyerahan tanpa gate yang bersih adalah kegagalan.
