# UI Engineering Knowledge Base

UI Engineering Knowledge Base adalah monorepo yang berfungsi sebagai perpustakaan pengetahuan untuk UI Engineering.

Repository ini mengorganisasi pengetahuan tentang bagaimana membangun user interface yang scalable, maintainable, dan performant di platform web.

Tujuan utama repository ini:

- membangun arsitektur pengetahuan UI engineering
- mendokumentasikan prinsip-prinsip UI modern
- menyediakan referensi yang terus berkembang
- membantu engineer memahami UI sebagai disiplin engineering, bukan sekadar penggunaan framework

Repository ini adalah monorepo jangka panjang yang selalu hidup: kontennya dirancang untuk terus diperbarui, direvisi, dan diperluas seiring perubahan praktik UI Engineering.

---

## Philosophy

UI Engineering bukan hanya tentang framework seperti React, Vue, atau Svelte.

UI Engineering adalah tentang:

- arsitektur UI
- sistem komponen
- manajemen state
- sinkronisasi data
- performa aplikasi
- aksesibilitas
- sistem desain

Framework hanyalah alat implementasi.

Repository ini fokus pada konsep dan sistem, bukan teknologi tertentu.

---

## Knowledge Architecture

Repository ini disusun sebagai rak buku teknik:

- Level root: penjelasan umum monorepo (`README.md`)
- Detail tambahan: dokumentasi lanjutan (`docs/`)
- Rak bernomor: `R01`, `R02`, `R03`, ...
- Buku bernomor di dalam rak: `B01`, `B02`, `B03`, ...

Setiap rak dan setiap buku memiliki `README.md` dan folder `docs/` masing-masing.

---

## Initial Library (First 20 Books)

Library dimulai dengan 20 buku inti yang tersebar di 7 rak:

- `R01-ui-fundamentals` (6 buku)
- `R02-component-systems` (4 buku)
- `R03-application-architecture` (2 buku)
- `R04-state-management` (3 buku)
- `R05-data-fetching` (2 buku)
- `R06-performance-engineering` (1 buku)
- `R07-accessibility-engineering` (2 buku)

Catatan: 20 buku ini adalah titik awal, bukan batas akhir. Struktur repository ini dirancang agar jumlah rak dan buku dapat terus bertambah.

---

## Repository Structure

```text
ui-engineering-knowledge-base
|-- README.md
|-- docs
|   |-- README.md
|   |-- ROOT_RULES.md
|   `-- RAK_INDEX.md
|-- R01-ui-fundamentals
|   |-- README.md
|   |-- docs
|   |   `-- RAK_RULES.md
|   `-- B01-rendering-model
|       |-- README.md
|       `-- docs
|           |-- BOOK_RULES.md
|           `-- CHANGELOG.md
`-- R02...R07 (pola sama)
```

---

## Governance Summary

- `README.md` root untuk konteks umum repository.
- Penjelasan detail yang terlalu panjang ditaruh di `docs/`.
- Aturan rak ditaruh di `Rxx-*/docs/RAK_RULES.md`.
- Aturan buku ditaruh di `Rxx-*/Byy-*/docs/BOOK_RULES.md`.
- Log versi hanya ada di `Rxx-*/Byy-*/docs/CHANGELOG.md`.

---

## Reference Policy

- Root menjelaskan kebijakan referensi tingkat monorepo.
- Tiap rak menjelaskan konteks referensi domainnya di `Rxx-*/README.md`.
- Detail referensi per topik ditulis di buku terkait, dan dicatat per perubahan pada changelog buku.
- Prioritaskan referensi primer (dokumentasi resmi, spesifikasi, RFC, paper, atau sumber otoritatif setara).

---

## Long-Term Vision

UI Engineering Knowledge Base dirancang untuk terus berkembang menjadi referensi UI engineering yang lengkap, terstruktur, dan konsisten.

Seiring berkembangnya ekosistem web, library ini dapat diperluas ke:

- advanced state management
- real-time UI systems
- large-scale frontend architecture
- complex interaction systems
- performance at scale
- design system governance

---

## Status

Early stage knowledge library.

Initial focus: 20 core books.
