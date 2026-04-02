# Telegram Auto-Forward Bot

Telegram xabarlarini avtomatik forward qilish vositasi.

## ⚡ O'rnatish

```bash
pip install -r requirements.txt
cp .env.example .env
# .env faylni to'ldiring
python bot.py
```

## ⚙️ Sozlamalar (.env)

```ini
API_ID=your_api_id
API_HASH=your_api_hash
SESSION_STRING=your_session_string
MESSAGE_LINK=https://t.me/channel/123
INTERVAL_HOURS=6
```

## 🔐 Xavfsizlik

- `.env` faylni **hech kimga** ko'rsatmang
- `SESSION_STRING` orqali akkauntga to'liq kirish mumkin
- GitHub'ga push qilishdan oldin `.env` `.gitignore` da ekanini tekshiring

## 📝 Eslatma

Telegram xizmat shartlariga rioya qiling. Spam uchun ishlatilishi akkaunt bloklanishiga olib kelishi mumkin.
