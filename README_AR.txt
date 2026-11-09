حزمة موقع ISLAM CHIC الكاملة للنقل والنشر عبر GitHub وNetlify

محتويات الحزمة:
- index.html: الموقع الكامل، ويتضمن إعداد Firebase الموجود في النسخة الحالية وتسجيل دخول المدير.
- netlify.toml: إعدادات نشر الموقع على Netlify.
- FIREBASE_SETUP_AR.txt: خطوات ربط نطاق Netlify مع Firebase وملاحظات قاعدة البيانات.

النشر:
1. فك ضغط هذا الملف.
2. ارفع الملفات الثلاثة الموجودة داخل المجلد إلى جذر مستودع جديد في GitHub.
3. في Netlify اختر Add new project ثم Import an existing project.
4. اربط GitHub واختر المستودع.
5. اجعل Publish directory = . واترك Build command فارغًا ثم انشر.
6. افتح رابط HTTPS الذي يعطيك Netlify.

مهم: ملف الموقع لا يحتوي على نسخة من بيانات قاعدة Firestore. بيانات الطلبات تبقى في مشروع Firebase السحابي، ولا تنتقل بمجرد نقل ملفات الموقع.
