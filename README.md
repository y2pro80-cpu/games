# تحدّي الكنبة — GitHub Pages

نسخة Static بالكامل، بدون Backend أو قاعدة بيانات أو سيرفر خاص.

## الرفع إلى GitHub Pages

1. ارفع **محتويات هذا المجلد** إلى جذر مستودع GitHub.
2. من `Settings → Pages` اختر فرع `main` ومجلد `/(root)`.
3. افتح رابط GitHub Pages.

التنقل يستخدم Hash Routing، لذلك تعمل الروابط داخل GitHub Pages:

- `#/` لوحة اللعبة.
- `#/join` دخول اللاعبين.
- `#/leader` دخول ليدر اللعبة.
- `#/screen` شاشة الجمهور.

## هيكل الملفات

```text
index.html
404.html
.nojekyll
README.md
assets/
  *.css
  *.js
```

بنك الأسئلة وإعدادات اللعبة تحفظ محليًا في متصفح جهاز المقدم باستخدام `localStorage`. لا توجد مزامنة بين أجهزة مختلفة لأن الموقع Static.
