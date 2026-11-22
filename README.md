# LuminaSkin.ai - Smart Facial Skin Analysis & Skincare Recommendation

Aplikasi web pendeteksi kondisi kulit wajah menggunakan teknologi Computer Vision dan kurasi rekomendasi skincare Indonesia (Skintific, Somethinc, Wardah, The Originote, COSRX, Azarine, dll.) berdasarkan analisis bahan aktif dan preferensi pengguna.

## Fitur Utama

- **Skin Scan**: Menggunakan kamera langsung (webcam) atau unggah foto wajah.
- **Visual Hotspots & Heatmap**: Menandai area masalah kulit (T-Zone sebum, jerawat aktif, pori terbuka, eritema/kemerahan).
- **Skin Health Scoring**: Penilaian skor kesehatan kulit (0 - 100) dan pengelompokan tipe kulit.
- **Ingredient Matching Strategy**: Rekomendasi bahan aktif target (Ceramide, Salicylic Acid, Niacinamide, dll) serta bahan yang harus dihindari.
- **Smart Product Recommendations**:
  - Filter waktu pemakaian: Pagi (AM) vs Malam (PM).
  - Filter anggaran: Terjangkau (< 100rb) vs Menengah (100rb - 250rb).
  - Filter aman ibu hamil & menyusui (*Bumil Friendly*).
  - Popup detail produk & alasan dermatologis.

## Cara Menjalankan

Aplikasi ini dapat dijalankan menggunakan web server statis apa pun:

```bash
# Menggunakan Python
python3 -m http.server 3000

# Atau buka index.html langsung di browser
```
