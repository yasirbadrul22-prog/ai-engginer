%%writefile README.md
# API Prediksi Kelulusan

API sederhana menggunakan FastAPI.

## Endpoint
- GET / : memeriksa status API
- POST /predict : memprediksi kelulusan dari nilai

## Aturan
Nilai >= 75: Lulus
Nilai < 75: Belum Lulus