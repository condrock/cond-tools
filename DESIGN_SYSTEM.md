# DESIGN_SYSTEM.md

# Cond Tools Design System

Version: 1.0

---

# 1. Design Philosophy

Cond Tools harus memiliki tampilan yang:

- Modern
- Minimalist
- Professional
- Fast
- Clean
- Premium
- Friendly
- Easy to Read

Fokus utama adalah usability.

Jangan menggunakan elemen dekoratif berlebihan.

---

# 2. Theme

Dark Mode Only.

Tidak menyediakan Light Mode.

Semua halaman wajib menggunakan tema yang sama.

---

# 3. Design Principles

Prioritas:

1. Readability
2. Simplicity
3. Speed
4. Accessibility
5. Consistency

---

# 4. Color Palette

Background

Primary Background

#0F1115

Secondary Background

#171B22

Card Background

#1D232D

Border

#2A3442

Primary Text

#FFFFFF

Secondary Text

#A8B3C7

Muted Text

#7B8798

Primary Accent

#3B82F6

Success

#22C55E

Warning

#F59E0B

Danger

#EF4444

Info

#06B6D4

---

# 5. Typography

Font Family

System UI

Fallback

sans-serif

Gunakan font bawaan sistem.

Tidak menggunakan Google Fonts.

Alasan:

- Lebih cepat
- Lebih ringan
- Tidak bergantung CDN

---

# 6. Font Size

Hero

40px

H1

32px

H2

28px

H3

22px

H4

18px

Body

16px

Small

14px

Caption

13px

---

# 7. Font Weight

Regular

400

Medium

500

Semi Bold

600

Bold

700

---

# 8. Border Radius

Small

8px

Medium

12px

Large

18px

Button

12px

Card

18px

Input

12px

---

# 9. Shadow

Gunakan shadow lembut.

Tidak menggunakan shadow besar.

Shadow hanya digunakan pada:

- Card
- Dropdown
- Modal

---

# 10. Layout

Container Max Width

1200px

Content Width

900px

Semua halaman berada di tengah.

---

# 11. Grid

Desktop

3-4 kolom

Tablet

2 kolom

Mobile

1 kolom

---

# 12. Spacing

Gunakan sistem spacing:

4

8

12

16

20

24

32

40

48

64

Jangan menggunakan nilai acak.

---

# 13. Buttons

Style

Rounded

Primary

Accent Color

Secondary

Border

Ghost

Transparent

Semua tombol memiliki:

Hover

Active

Focus

Disabled

---

# 14. Inputs

Rounded

Border Tipis

Focus Ring

Label selalu berada di atas.

Placeholder berwarna abu-abu.

---

# 15. Cards

Semua tools menggunakan card.

Card memiliki:

Radius

Shadow ringan

Padding konsisten

Hover Effect

---

# 16. Icons

Gunakan Material Symbols Rounded.

Ukuran default:

20px

24px

32px

Jangan mencampur berbagai library ikon.

---

# 17. Animation

Durasi

150–250ms

Gunakan:

Fade

Slide

Scale kecil

Hindari animasi berlebihan.

---

# 18. Navigation

Sticky Header

Desktop

Sidebar jika diperlukan.

Mobile

Hamburger Menu.

---

# 19. Breadcrumb

Semua halaman tools wajib memiliki breadcrumb.

---

# 20. Tool Page Structure

Header

↓

Breadcrumb

↓

Hero

↓

Description

↓

Input Card

↓

Generate Button

↓

Result Card

↓

FAQ

↓

Advertisement

↓

Related Tools

↓

Footer

---

# 21. Tool Card

Berisi:

Icon

Title

Description

Category

Button

Hover Effect

---

# 22. Result Card

Harus mudah dibaca.

Memiliki:

Copy Button

Reset

Download (jika diperlukan)

Share (opsional)

---

# 23. FAQ

Accordion.

Minimal:

5 pertanyaan.

---

# 24. Advertisement

Maksimal satu slot.

Responsive.

Tidak mengganggu.

Tidak sticky.

---

# 25. Footer

Berisi:

About

Categories

Contact

Privacy

Disclaimer

Copyright

---

# 26. Mobile Rules

Target utama adalah mobile.

Semua komponen harus nyaman digunakan dengan satu tangan.

Ukuran tombol minimal:

44px

---

# 27. Accessibility

Kontras tinggi.

Keyboard Friendly.

ARIA jika diperlukan.

Semantic HTML.

---

# 28. Performance

Tidak menggunakan:

Bootstrap

Tailwind

jQuery

Framework CSS

Framework JavaScript

---

# 29. Empty State

Jika tools belum menghasilkan output:

Tampilkan ilustrasi sederhana atau pesan ramah.

---

# 30. Coming Soon

Gunakan card khusus.

Jangan hanya menampilkan tulisan:

Coming Soon.

Harus menjelaskan:

- Fungsi tools.
- Manfaat.
- Status pengembangan.

---

# 31. Error State

Pesan error harus:

Singkat

Jelas

Mudah dipahami

Tidak menggunakan istilah teknis.

---

# 32. Success State

Gunakan warna hijau.

Sertakan ikon centang.

---

# 33. Loading

Gunakan Skeleton Loading.

Jangan menggunakan spinner besar.

---

# 34. Image

Gunakan SVG bila memungkinkan.

Hindari gambar besar.

---

# 35. Branding

Logo sederhana.

Flat Design.

Tanpa efek 3D.

---

# 36. Overall Feel

Website harus terasa seperti:

Produk profesional.

Bukan template gratis.

Bukan blog.

Bukan dashboard admin.

Melainkan aplikasi web modern yang cepat, ringan, dan fokus pada produktivitas.
