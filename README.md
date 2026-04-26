# 🌙 Smart Azkar Telegram Bot

by GENERAL DEV 🚀

«🤖 A professional Telegram bot for sending Islamic azkar with gamification and smart engagement.
🤖 بوت تيليجرام احترافي لإرسال الأذكار مع نظام نقاط وتحفيز المستخدم.»

---

✨ Features | المميزات

🇬🇧 English

- "/start" command with interactive buttons
- Sends random azkar periodically (every hour)
- No repeated azkar consecutively
- Gamification system (points + levels)
- Motivational messages every 10 azkar
- Multi-user support
- Persistent data storage (JSON)

🇸🇦 العربية

- أمر "/start" مع أزرار سهلة الاستخدام
- إرسال أذكار بشكل دوري (كل ساعة)
- عدم تكرار نفس الذكر مرتين متتاليتين
- نظام نقاط ومستويات للمستخدم
- رسائل تحفيزية كل 10 أذكار
- يدعم عدد كبير من المستخدمين
- حفظ بيانات المستخدمين تلقائيًا

---

🧠 Architecture | البنية

- Telegram Bot API
- Background Thread Scheduler
- JSON Database
- Event-driven Handlers

---

🔐 Environment Setup | إعداد التشغيل

🇬🇧

Set your bot token using environment variables:

🇸🇦

قم بإضافة توكن البوت بطريقة آمنة:

BOT_TOKEN=your_token_here

---

▶️ Run the Bot | تشغيل البوت

pip install -r azkar-bot/requirements.txt
python azkar-bot/bot.py

---

🧪 Testing | التجربة

🇬🇧

Change interval for testing:

🇸🇦

لتجربة أسرع:

ZIKR_INTERVAL_SECONDS = 60

---

📁 Project Structure | هيكل المشروع

azkar-bot/
├── bot.py
├── requirements.txt
├── README.md
└── users_data.json

---

🚀 Future Plans | التطوير المستقبلي

🇬🇧

- Database upgrade (SQLite / PostgreSQL)
- Admin dashboard
- Cloud hosting

🇸🇦

- استخدام قاعدة بيانات احترافية
- لوحة تحكم للأدمن
- استضافة على سيرفر دائم

---

💡 Developer | المطور

YOUSSEF ELGENERAL DEV
بوتات – ذكاء اصطناعي – أمن سيبراني

---

🤲 Final Message | كلمة أخيرة

May Allah accept from us and from you 🤲
نسأل الله القبول لنا ولكم 🤲

---

⭐ Star the repo if you like it
⭐ لا تنسى دعم المشروع بنجمة ⭐