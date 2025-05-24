# AutoTradeGovinda (Render Edition)

Ini adalah versi deploy ke [Render.com](https://render.com) dari bot auto trading Indodax via Telegram + webhook.

## File Penting
- `run_bot.py`: Menjalankan Flask + Telegram bot
- `requirements.txt`: Daftar dependensi Python
- `Procfile`: Diperlukan oleh Render untuk memulai bot

## Cara Deploy (Gratis)
1. Buat akun di https://render.com
2. Klik **New Web Service**
3. Hubungkan dengan repo GitHub kamu (upload semua file ini)
4. Pilih:
   - **Environment**: Python 3
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `python run_bot.py`
   - **Free Plan**: ✅
5. Setelah deploy selesai, copy URL `https://your-service.onrender.com/sinyal`
6. Tempel URL itu di Google Apps Script (untuk auto-trigger dari Google Sheets)

**Selesai. Bot kamu akan aktif 24 jam nonstop gratis!**
