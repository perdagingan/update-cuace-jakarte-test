# Prakiraan Suhu Jakarta

Proyek ini menampilkan data prakiraan suhu per jam Jakarta dari API Open-Meteo.

## Fitur

- Menampilkan prakiraan suhu per jam untuk Jakarta
- Data diambil dari API Open-Meteo
- Tampilan dalam format tabel yang mudah dibaca

## Data yang Ditampilkan

| Field | Deskripsi |
|-------|-----------|
| `time` | Waktu pengukuran |
| `temperature_2m` | Suhu dalam °C |

## Sumber Data

API URL: `https://api.open-meteo.com/v1/forecast?latitude=-6.2&longitude=106.8&hourly=temperature_2m`

- Latitude: -6.2 (Jakarta)
- Longitude: 106.8 (Jakarta)

## Cara Menggunakan

1. Buka file `index.html` di browser
2. Data prakiraan suhu akan dimuat secara otomatis
3. Tabel akan menampilkan waktu dan suhu per jam

## Teknologi

- HTML5
- CSS3
- JavaScript (Vanilla)
- Open-Meteo API