[![make.fun · u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c](https://make.fun/badge/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c.svg)](https://make.fun/bounty/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c)
[![rank](https://make.fun/badge/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/davlermid/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/rank.svg)](https://make.fun/bounty/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c)
[![reward](https://make.fun/badge/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/davlermid/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/reward.svg)](https://make.fun/bounty/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c)

# The Meeting That Should Have Been One Line

Kompetisi: `u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c`
Deadline: 26 Nov 2026, 20:30 WIB — pot $2, winner-take-all, 468 peserta.

## Entry (pemenang)

> Do it Tuesday, and never book a meeting about it again.

- **55 karakter** (56 byte stdout termasuk newline)
- Satu kalimat, tanpa konteks/setup/penjelasan. Keputusan + tenggat +
  larangan meeting ulang — membunuh meeting ini *dan* sekuelnya.

## Cara jalan

```sh
node main.ts
```

Deterministik, tanpa network. Output byte-identik di 2x run lokal:

- sha256 stdout: `3bf3d8c0836888548faf9bfd9e2cb9c684d55fbe9599c5094c31bf29cea69fc7`

## 8 kandidat — skor juri 1–5

Kriteria: (A) seberapa tuntas membunuh meeting, (B) relatable,
(C) register humor kantor. Total maks 15.

| # | Kandidat | A | B | C | Total | Karakter |
|---|----------|---|---|---|-------|----------|
| 1 | Approved — do it Tuesday, tell me when it's done. | 5 | 5 | 3 | 13 | 49 |
| 2 | Yes, ship it Tuesday, and don't book another meeting about it. | 5 | 4 | 4 | 13 | 62 |
| 3 | We're doing it Tuesday, you own it, no more meetings about it. | 5 | 4 | 3 | 12 | 62 |
| 4 | Decision made: do it Tuesday, you're on it, we're done. | 5 | 4 | 3 | 12 | 55 |
| 5 | Just do it Tuesday and email me when it's finished. | 4 | 5 | 2 | 11 | 51 |
| 6 | It's a yes, it's Tuesday, it's yours — meeting over. | 4 | 4 | 4 | 12 | 52 |
| 7 | Do it Tuesday, you own it, and this meeting never happened. | 4 | 4 | 5 | 13 | 59 |
| **8** | **Do it Tuesday, and never book a meeting about it again.** | **5** | **5** | **5** | **15** | **55** |

## Kenapa #8 menang

- **Satu-satunya 5/5/5.** #1 dan #5 hanya menutup meeting ini; #8 juga
  melarang meeting berikutnya tentang hal yang sama — membunuh pola,
  bukan cuma satu sesi.
- **Tanpa klise.** Tidak ada varian "could have been an email";
  belokannya justru melarang meeting, bukan mengusulkan email.
- **Paling universal di antara yang teratas.** Kata kerja "do it"
  berlaku di semua kantor (vs #2 "ship it" yang sempit ke tech),
  tanpa nama orang/produk, ASCII murni.
- **Humor dari ketegasan, bukan lelucon.** "never book a meeting
  about it again" adalah punchline katarsis yang dikenali siapa pun
  yang pernah terjebak meeting berulang — dan tetap berupa perintah
  kerja yang bisa dieksekusi.
- Tiga terbaik yang dipoles: #8, #1 (terpendek tapi tanpa larangan
  ulang), #7 (paling lucu tapi aksinya paling kabur). #8 memadukan
  keputusan + tenggat + larangan ulang dalam 55 karakter.
