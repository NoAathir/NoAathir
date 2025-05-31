# NoAathir

**منصة عربية العلامات التجارية عبر المؤثرين**

## المرحلة 0: التحضير
- **اسم المنصة:** نؤثر / NoAathir
- **البريد الإلكتروني:** noaathir.platform@gmail.com
- **الهاتف/واتساب:** +967 702 522 260 / +967 702 522 261
- **النطاق (Beta):** https://noaathir.vercel.app
- **التقنيات:** Flutter + Firebase (Auth, Firestore, Functions) + Vercel
- **اللغات:** العربية (RTL) والإنجليزية

### الميزات الأساسية (MVP)
1. تسجيل/دخول آمن (Firebase Auth)
2. بروفايل مؤثر مفصل
3. بحث/فلترة متقدمة
4. إنشاء حملات (محاكاة Sandbox)
5. لوحة إدارة المستخدمين والحملات
6. نظام مراسلة داخلي
7. بوابة دفع تجريبية (Sandbox Payment Simulation)
8. إشعارات وتنبيهات
9. تقييم ومراجعات بعد الحملة
10. لوحة إحصائيات بسيطة
11. نظام تذاكر دعم
12. API مفتوح (REST) باستخدام Cloud Functions


## هيكل المجلدات المقترح
NoAathir/ ├── .gitignore ├── README.md ├── docs/ │   ├── ContentPlan.docx │   ├── InfluencerProfileTemplate.docx │   ├── LegalChecklist.docx │   └── FeatureBacklog.xlsx ├── lib/                  # كود Flutter الرئيسي سيأتي هنا ├── assets/               # الصور والشعارات (logo, icons) ├── firebase/             # إعدادات Firebase (firestore.rules, functions) ├── android/              # مجلد مشروع أندرويد التابع لـ Flutter ├── ios/                  # مجلد مشروع iOS التابع لـ Flutter ├── web/                  # ملفات الويب (لـ PWA) عندما نبني Flutter Web ├── test/                 # اختبارات Flutter (Unit & Integration) ├── pubspec.yaml          # تعريف الحزم (dependencies) والإعدادات العامة └── firebase_options.dart # ملف التكوين التلقائي لـ Firebase (سينتج عبر flutterfire configure)

(يمكنك تعديل الوصف لاحقًا بإضافة أو حذف أي فقرة)

**لمزيد من التفاصيل، راجع مجلد** `/docs` (الموجود حاليًا كقوالب فارغة).
