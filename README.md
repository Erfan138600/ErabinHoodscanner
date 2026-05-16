# ErabinHood Scanner ⚡

<p align="center">
  اسکنر حرفه‌ای IP با رابط کاربری نئونی برای پیدا کردن IPهای زنده و کم‌تاخیر
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-v2.0-00f0ff?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Web-8a2bff?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-ff00e6?style=for-the-badge">
</p>

---

# ✨ Features

- پشتیبانی از:
  - IP تکی
  - CIDR
  - بازه IP
- اسکن همزمان (Concurrency)
- رابط کاربری Neon UI
- مرتب‌سازی نتایج بر اساس Latency
- خروجی TXT و CSV
- پشتیبانی از رنج‌های آماده Akamai
- بدون نیاز به بک‌اند
- اجرا مستقیم در مرورگر
- سازگار با:
  - Windows
  - Linux
  - Android
  - macOS

---

# 📸 Preview

## Neon Interface

- رابط کاربری سایبرپانک
- انیمیشن‌های نئونی
- جدول نتایج حرفه‌ای
- آمار لحظه‌ای اسکن
- Progress Bar زنده

---

# 🚀 Run

فقط فایل زیر را اجرا کنید:

```bash
ErabinHood_Scanner.html
```

یا فایل را داخل مرورگر Drag & Drop کنید.

---

# 📥 Input Formats

## Single IP

```txt
104.64.0.5
```

## CIDR

```txt
23.72.0.0/24
```

## IP Range

```txt
2.16.0.1-2.16.0.50
```

---

# ⚙ Settings

| Option | Description |
|---|---|
| Concurrency | تعداد درخواست همزمان |
| Timeout | زمان انتظار پاسخ |
| Max IPs | حداکثر IP برای تست |

---

# 📊 Export

## TXT Export

خروجی لیست IPهای زنده:

```txt
104.64.0.1
104.64.0.2
```

---

## CSV Export

شامل:

- IP
- Latency
- Status

---

# 🧠 How It Works

اسکنر با استفاده از:

```js
fetch()
```

و حالت:

```js
mode: "no-cors"
```

و ارسال درخواست HTTPS وضعیت IPها را بررسی می‌کند.

---

# 🔥 Built-in Features

- توقف اسکن در لحظه
- انتخاب تصادفی IP در رنج‌های بزرگ
- تشخیص کیفیت اتصال:
  - Excellent
  - Good
  - Medium
  - Slow

---

# 📡 Official Links

- Telegram Channel: https://t.me/erfwp
- Telegram Bot: https://t.me/ErabinHood
- Website: https://erfwp.ir

---

# 👨‍💻 Developer

Made with ⚡ by **ErabinHood** - ERFAN

---

# ⚠ Disclaimer

این ابزار صرفاً برای اهداف آموزشی، تست شبکه و بررسی CDN ساخته شده است.

مسئولیت استفاده نادرست بر عهده کاربر خواهد بود.

---

