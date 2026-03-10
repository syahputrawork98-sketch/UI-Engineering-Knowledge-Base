# ROOT Rules

## Scope

Berlaku untuk level root repository.

## Root Policy

- Root hanya berisi `README.md`, folder `docs/`, dan folder `RAK` (`R01...Rnn`).
- Penjelasan umum monorepo ada di `README.md`.
- Penjelasan detail dan aturan tambahan ada di `docs/`.

## Layer Model

- Layer 1: `ROOT`
- Layer 2: `RAK` (`Rxx-*`)
- Layer 3: `BUKU` (`Bxx-*`)

## Numbering

- RAK: `R01`, `R02`, `R03`, ...
- BUKU: `B01`, `B02`, `B03`, ... (lokal per RAK)
- ID lengkap buku untuk referensi versi: `Rxx-Byy`

## Versioning

- Changelog hanya ada di level buku pada `docs/CHANGELOG.md`.
- Tidak ada changelog versi konten di level ROOT atau RAK.
