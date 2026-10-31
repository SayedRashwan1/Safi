# صافي — تنقية الصوت والفيديو بالذكاء الاصطناعي

أداة مجانية لتنقية الصوت (بديل لـ Adobe Podcast Enhance) تشتغل بالكامل داخل المتصفح:
لا رفع ملفات، لا تسجيل دخول، لا حدود للمدة. تشتغل كموقع على الويب، وكبرنامج يتثبّت على الماك والويندوز (PWA) ويعمل بدون إنترنت.

**الموقع:** https://elsayedsamirgaber.github.io/Safi/

## المميزات
- إزالة الضوضاء بالذكاء الاصطناعي (DeepFilterNet3) + محرك سريع (RNNoise)
- تنظيف الفواصل بين الجمل، إزالة الطنين 50/60 هرتز، تخفيف السين (De-esser)
- تحسين النبرة (EQ)، ضغط ديناميكي، ضبط مستوى الصوت القياسي (LUFS)
- مقارنة فورية قبل/بعد
- تصدير الفيديو بنفس جودة الصورة الأصلية، أو صوت MP4، أو WAV كامل الجودة
- سجل يومي/شهري بكل الملفات مع تصدير CSV

## التثبيت كبرنامج
- **Chrome / Edge (ويندوز وماك):** افتح الموقع ← زر «ثبّت البرنامج».
- **Safari على الماك:** File ← Add to Dock.

## مكتبات مفتوحة المصدر مستخدمة
- [DeepFilterNet](https://github.com/Rikorose/DeepFilterNet) — MIT / Apache-2.0 (بناء WASM من `@lofcz/deepfilternet-web`)
- [RNNoise WASM](https://github.com/shiguredo/rnnoise-wasm) — Apache-2.0
- [Mediabunny](https://github.com/Vanilagy/mediabunny) — MPL-2.0
