# 🔐 Pigpen Cipher Toolkit

> أداة احترافية متكاملة لترميز وفك تشفير **شفرة بيجبن (Pigpen Cipher)** — تعمل بالكامل داخل ملف HTML واحد، بدون إنترنت وبدون أي مكتبات خارجية.
>
> A complete, professional **Pigpen Cipher** encode/decode toolkit — runs entirely from a single HTML file, fully offline, zero external dependencies.

![Offline](https://img.shields.io/badge/Offline-100%25-33e19a) ![Dependencies](https://img.shields.io/badge/Dependencies-0-00e5ff) ![License](https://img.shields.io/badge/License-MIT%20%2B%20Attribution-7b5cff)

---

## ✨ المميزات | Features

- 🔓 **Decode** — بناء رسالة بيجبن عبر لوحة الرموز مع ترجمة فورية للإنجليزية
- 🔐 **Encode** — تحويل النص الإنجليزي إلى رموز بيجبن في الزمن الحقيقي
- 📖 **Dictionary** — قاموس Offline داخلي للبحث والترجمة (بدون API)
- 🎯 **Practice** — وضع تدريبي تفاعلي لتعلم رموز بيجبن
- 🕓 **History** — حفظ آخر 50 عملية عبر LocalStorage
- ⭐ **Favorites** — تثبيت الكلمات المهمة في القاموس
- 📊 **Statistics** — عدد الرموز، الحروف، الكلمات، عمليات النسخ/الترميز/فك التشفير
- 📥📤 **Import / Export** — TXT / JSON / CSV
- 🌐 **ثنائي اللغة** — عربي / إنجليزي مع تبديل فوري للاتجاه RTL ⇄ LTR
- 🎨 **4 ثيمات** — Cyberpunk, Hacker Green, Material Dark, AMOLED Black
- 🖼️ رموز بيجبن مرسومة هندسيًا عبر **SVG حقيقي** مطابق للشفرة الأصلية (وليس رموز يونيكود عشوائية)
- 🔔 Toast Notifications احترافية بدلًا من `alert()`
- ⚡ مبني بأداء عالٍ: Debounce, DocumentFragment, Event Delegation, DOM Caching

---

## 🚀 التشغيل | Usage

لا حاجة لأي تثبيت أو خادم. فقط:

1. حمّل ملف [`index.html`](./pigpen-cipher-toolkit.html)
2. افتحه مباشرة في أي متصفح حديث (Chrome / Edge / Firefox / Safari)
3. استمتع بالتطبيق كاملًا — Offline 100%

No installation, no build step, no server required:

```bash
# Just open the file directly
open index.html
```

---

## 🗂️ بنية المشروع | Project Structure

المشروع بالكامل داخل ملف واحد، لكنه منظم داخليًا بمعمارية واضحة:

```
index.html
├── CONFIG            // كل الإعدادات القابلة للتعديل (الثيمات، الحقوق، حدود السجل...)
├── STATE             // الحالة العامة للتطبيق
├── UI_TEXT           // نصوص الواجهة (عربي / إنجليزي)
├── DICTIONARY        // القاموس الداخلي Offline
├── CipherEngine       // محرك الترميز وفك التشفير + رسم رموز بيجبن SVG
├── TranslationEngine // محرك الترجمة Offline
├── StorageManager     // إدارة LocalStorage
├── HistoryManager      // إدارة سجل العمليات
├── StatsManager        // إدارة الإحصائيات
├── ThemeManager         // إدارة الثيمات
├── UIRenderer            // عرض وتحديث الواجهة
├── DecodeController       // منطق تبويب فك التشفير
├── PracticeEngine          // منطق وضع التدريب
└── Utils                    // دوال مساعدة عامة
```

---

## 🖥️ التقنيات | Tech Stack

- HTML5, CSS3 (Custom Properties, Glassmorphism, Animations)
- Vanilla JavaScript (ES6+) — **بدون أي مكتبة خارجية أو CDN**
- LocalStorage API فقط للتخزين المحلي

---

## 🤝 المساهمة | Contributing

المساهمات مرحّب بها! افتح Issue أو Pull Request وسيتم مراجعته.

Contributions are welcome — feel free to open an issue or a pull request.

---

## 📜 الترخيص | License

هذا المشروع مرخّص بموجب [MIT License](./LICENSE) **مع شرط إلزامي بالحفاظ على حقوق الملكية والنسب (Attribution)** كما هو موضح في ملف الترخيص. لا يجوز إزالة أو تعديل اسم أو رابط المالك الأصلي من أي نسخة أو نسخة معدّلة من هذا المشروع.

This project is licensed under the [MIT License](./LICENSE) **with a mandatory attribution clause** — the original owner's name and link must not be removed or altered in any copy or derivative of this project.

---

## 👤 الحقوق والملكية | Credits & Ownership

هذا المشروع مملوك بالكامل لصاحبه، ويجب الحفاظ على ذكر اسمه في أي استخدام أو نسخة من هذا الكود:

<div align="center">

### 𝔐𝔬𝔥𝔞𝔪𝔪𝔞𝔡 𝕊𝔞𝔩𝔢𝔪 𓂀

🔗 **[shorturl.at/zj4Hc](https://shorturl.at/zj4Hc)**

</div>

> جميع الحقوق محفوظة © Mohammad Salem — All Rights Reserved.
