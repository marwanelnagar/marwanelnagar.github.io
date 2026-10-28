# نظام التيسير الذكي
تطبيق ويب عربي لإدارة طلاب حلقات القرآن والحضور والمدفوعات، مبني باستخدام HTML/CSS/JavaScript وFirebase Authentication وCloud Firestore.

## تشغيل التطبيق
- افتح مجلد `altayseer-smart-system` ثم ملف `index.html` عبر رابط GitHub Pages.
- فعّل Email/Password في Firebase Authentication.
- في Firebase Console > Firestore Database > Rules، انسخ محتوى `FIRESTORE_RULES.txt` وانشر القواعد.
- افتح التطبيق وأنشئ حساب إدارة ببريد إلكتروني وكلمة مرور من 6 أحرف على الأقل.
- أضف الطلاب من داخل التطبيق. سجّل الدخول بنفس الحساب على الهاتف والكمبيوتر لمزامنة البيانات.

## النشر
هذا المستودع هو موقع GitHub Pages الشخصي. افتح `Settings > Pages` وتأكد أن المصدر `Deploy from a branch` والفرع `main` والمجلد `/(root)`. رابط التطبيق:
https://marwanelnagar.github.io/altayseer-smart-system/

## الأمان
لا تفتح Firestore للعامة. القواعد المرفقة تسمح للمستخدم المسجل بالوصول إلى المسارات الخاصة بمعرّف حسابه فقط. هذا الإصدار مخصص لحساب إدارة، وليس به حسابات طلاب مستقلة بعد. لا تحفظ بيانات حساسة أكثر من اللازم.