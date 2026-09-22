# ساخت APK با خود گوشی (بدون AndroidIDE)

این پروژه برای ساخت APK با GitHub Actions آماده شده است. GitHub روی سرور خودش Gradle را اجرا می‌کند و APK را به‌صورت Artifact تحویل می‌دهد.

## چیزی که لازم داری
1. یک حساب GitHub.
2. یک پروژه Firebase.
3. فایل `google-services.json` مربوط به Android app را از Firebase بگیر و داخل پوشه `app/` قرار بده.

## ساخت با گوشی
1. در GitHub یک Repository جدید بساز.
2. فایل‌های این پروژه را داخل Repository آپلود کن.
3. فایل `app/google-services.json` را هم آپلود کن.
4. از تب **Actions**، workflow به نام **Build Otaghe Ma APK** را اجرا کن.
5. بعد از سبز شدن Build، در صفحه همان اجرای workflow بخش **Artifacts** را باز کن و `OtagheMa-debug-apk` را بگیر.

این APK نسخه تستی است و برای نصب مستقیم روی گوشی مناسب است.
