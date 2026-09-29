# تفعيل Firebase للعبة تحدّي الكنبة

الكود أصبح جاهزًا، وبقي تفعيل خدمتين في Firebase Console:

1. **Authentication → Sign-in method → Anonymous → Enable**.
2. **Realtime Database → Rules** ثم لصق محتوى `firebase.database.rules.json`.

بعد الحفظ، ارفع مجلد `dist/public` إلى GitHub Pages. كل غرفة لها رمز يظهر في لوحة الليدر، وباركود اللاعبين يحتوي رابط الغرفة.

> إعدادات Firebase Web موجودة في `client/src/lib/firebase.ts`، وهي ليست كلمة مرور. لا تضف مفاتيح Admin SDK إلى الواجهة.
