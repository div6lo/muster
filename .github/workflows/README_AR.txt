Muster Personal - Android Studio project

هذا مشروع Android WebView مستقل يحتوي على نسخة HTML الحالية داخل assets.

لإنشاء APK:
1) افتح مجلد MusterPersonal في Android Studio.
2) انتظر Gradle Sync وتنزيل Android SDK Platform 35 عند الطلب.
3) من القائمة Build اختر Build Bundle(s) / APK(s) ثم Build APK(s).
4) ملف APK الناتج سيكون عادة داخل app/build/outputs/apk/debug/app-debug.apk

ملاحظات:
- التطبيق يعمل بواجهة محلية دون تسجيل دخول أو اتصال بسيرفر الجامعة.
- اختيار الصور يتم من معرض الجهاز، والتغييرات تحفظ محليًا داخل WebView.
- هذا المشروع ليس تطبيقًا رسميًا للجامعة ولا يتصل بأنظمتها.
- لم يتم تضمين APK جاهز؛ بيئة التنفيذ الحالية لا تحتوي على Android SDK أو Gradle، لذلك لا يمكن إجراء عملية compile هنا.
