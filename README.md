# ⚡ DevMind AI — مساعد المطورين الذكي

<div align="center">

![DevMind AI](https://img.shields.io/badge/DevMind-AI%20Powered-7c6fff?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-Sonnet%204-a78bfa?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-Single%20File-orange?style=for-the-badge&logo=html5)
![License](https://img.shields.io/badge/License-MIT-4ade80?style=for-the-badge)

**أداة ذكاء اصطناعي متكاملة للمطورين — كل ما تحتاجه في ملف HTML واحد.**

[🚀 تجربة مباشرة](#تشغيل) · [📸 لقطات الشاشة](#لقطات) · [🛠️ الميزات](#الميزات)

</div>

---

## ✨ الميزات

| الأداة | الوصف |
|--------|-------|
| 💻 **مساعد الكود** | اكتب كوداً نظيفاً بأي لغة برمجة مع شرح تفصيلي |
| 🔍 **مراجعة الكود** | تحليل عميق للكود وكشف الثغرات ومقترحات التحسين |
| 🐛 **تصحيح الأخطاء** | تحديد الأخطاء وشرح أسبابها مع الحلول الصحيحة |
| 📖 **شرح المفاهيم** | شرح مبسط لأصعب المفاهيم مع أمثلة عملية |
| 🏗️ **تصميم المعمارية** | بناء معمارية أنظمة كبيرة وقابلة للتوسع |
| ✅ **كتابة الاختبارات** | اختبارات شاملة (Unit, Integration, E2E) |
| 🗄️ **استعلامات SQL** | كتابة وتحسين استعلامات قواعد البيانات |
| 🌿 **مساعد Git** | أوامر Git المتقدمة وإدارة الإصدارات |

---

## 🚀 تشغيل

### الطريقة الأسرع (بدون أي تثبيت)
```bash
# 1. استنسخ المستودع
git clone https://github.com/YOUR_USERNAME/devmind-ai.git

# 2. افتح الملف في المتصفح مباشرة
open dev-ai-assistant.html
# أو على Windows:
start dev-ai-assistant.html
```

> **ملاحظة:** الأداة تعمل مباشرة من المتصفح — لا يوجد خادم أو تثبيت مطلوب!

---

## ⚙️ الإعداد

### ربط مفتاح Anthropic API

الأداة تستخدم Claude API من Anthropic. لتفعيلها:

1. احصل على مفتاح API مجاني من [console.anthropic.com](https://console.anthropic.com)
2. افتح الملف `dev-ai-assistant.html` في محرر النصوص
3. الأداة مُضمَّنة بالفعل — تأكد من تشغيلها عبر خادم يدعم الطلبات الخارجية

**أو استخدم مع Claude.ai المضمَّن:**
إذا كنت تستخدم هذه الأداة داخل بيئة claude.ai، تعمل تلقائياً بدون أي مفتاح.

---

## 🗂️ هيكل المشروع

```
devmind-ai/
│
├── dev-ai-assistant.html   # الأداة الكاملة (ملف واحد)
├── README.md               # هذا الملف
└── LICENSE                 # رخصة MIT
```

> كل شيء في ملف HTML واحد — لا dependencies، لا npm، لا node_modules! 🎉

---

## 🎨 التقنيات المستخدمة

- **Frontend:** HTML5 + CSS3 + Vanilla JavaScript (بدون أي framework)
- **AI Engine:** Claude Sonnet 4 (Anthropic)
- **الخطوط:** IBM Plex Sans Arabic + JetBrains Mono + Space Grotesk
- **التصميم:** Dark theme مع تأثيرات CSS متقدمة

---

## 💡 أمثلة الاستخدام

### كتابة كود
```
اكتب لي خوارزمية Binary Search بلغة Python مع شرح الكود
```

### مراجعة كود
```
راجع هذا الكود وأخبرني عن المشاكل:
function fetchUser(id) {
  return fetch('/api/users/' + id).then(r => r.json())
}
```

### تصميم نظام
```
صمم معمارية نظام Twitter يدعم 100 مليون مستخدم
```

---

## 🤝 المساهمة

نرحب بمساهماتك! للمساهمة:

1. **Fork** المستودع
2. أنشئ فرع جديد: `git checkout -b feature/amazing-feature`
3. أضف تغييراتك: `git commit -m 'feat: add amazing feature'`
4. ارفع التغييرات: `git push origin feature/amazing-feature`
5. افتح **Pull Request**

---

## 📋 خارطة الطريق

- [ ] 🌐 دعم نماذج AI متعددة (GPT-4, Gemini)
- [ ] 💾 حفظ المحادثات محلياً
- [ ] 📤 تصدير الكود مباشرة
- [ ] 🎨 ثيمات قابلة للتخصيص
- [ ] 🔌 إضافة كـ VS Code Extension

---

## 📄 الرخصة

هذا المشروع مرخص تحت رخصة **MIT** — انظر ملف [LICENSE](LICENSE) للتفاصيل.

---

<div align="center">

صُنع بـ ❤️ للمطورين العرب

⭐ إذا أعجبتك الأداة، لا تنسَ إضافة نجمة للمستودع!

</div>
