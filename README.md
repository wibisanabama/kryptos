# Kryptos

Kryptos adalah dashboard web untuk memantau harga dan data pasar cryptocurrency menggunakan CoinGecko API.

## Fitur

- Statistik pasar cryptocurrency global
- Harga, market cap, volume, dan perubahan harga cryptocurrency
- Pencarian cryptocurrency
- Pilihan mata uang USD, IDR, EUR, JPY, dan GBP
- Grafik harga berdasarkan rentang waktu
- Daftar cryptocurrency trending, top gainers, dan top losers
- Pagination dan pilihan jumlah data per halaman
- Pembaruan data otomatis setiap 60 detik
- Tampilan responsif untuk desktop dan perangkat seluler

## Teknologi

- HTML
- CSS
- JavaScript
- CoinGecko API

Project ini tidak menggunakan framework, backend, database, atau build tool.

## Persyaratan

- Browser modern dengan dukungan JavaScript
- CoinGecko Demo API key

## Instalasi

1. Buka terminal pada direktori root project.

2. Salin file konfigurasi menjadi `config.js`.

   ```bash
   cp config.example.js config.js
   ```

3. Isi CoinGecko API key pada `config.js`.

   ```js
   const CONFIG = {
     COINGECKO_API_KEY: "YOUR_API_KEY",
   };
   ```

4. Buka `index.html` pada browser.

## Struktur Project

```text
kryptos-website/
|-- index.html
|-- style.css
|-- script.js
|-- config.example.js
`-- README.md
```

## Konfigurasi

`config.js` digunakan untuk menyimpan CoinGecko Demo API key secara lokal dan tidak disertakan dalam repository.

## Sumber Data

Seluruh data pasar cryptocurrency disediakan oleh [CoinGecko API](https://www.coingecko.com/api/documentation).
