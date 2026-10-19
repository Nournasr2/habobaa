# Habiba — Five Levels

لعبة رومانسية من 5 ليفلات بواجهة عربية RTL، جاهزة للنشر على GitHub Pages كـ PWA.

## تعديل الأسئلة والإجابات
افتح `app.js` وابحث عن `const levels`. عدّل `question` و`answer` و`title` لكل ليفل.

## النشر على GitHub Pages
1. أنشئ مستودعًا جديدًا مثل `habiba-five-levels`.
2. ارفع محتويات هذا المجلد إلى جذر المستودع بحيث يظهر `index.html` مباشرة.
3. افتح Settings → Pages.
4. اختر Deploy from a branch، ثم `main` و`/(root)` واضغط Save.
5. بعد النشر سيكون الرابط عادة `https://YOUR-USERNAME.github.io/habiba-five-levels/`.

## تثبيت الهاتف
Android: افتح الرابط في Chrome → القائمة → Install app أو Add to Home screen.
iPhone: افتح الرابط في Safari → Share → Add to Home Screen.

## التحويل إلى APK
المشروع PWA وليس APK بذاته. بعد نشره على HTTPS يمكن تغليفه كتطبيق Android باستخدام PWABuilder (Android package) أو Capacitor. لا ترفع مفاتيح التوقيع أو كلمات المرور إلى GitHub.

اللعبة لا تجمع إجابات الزائرة ولا ترسلها لأي مكان. الصوت اختياري ويبدأ بعد الضغط على زر الموسيقى.
