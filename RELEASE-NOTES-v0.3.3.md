# KingVPN v0.3.3 — Android

**Official KingServer Android release | انتشار رسمی نسخه اندروید**

## 🇮🇷 تغییرات
- بهبود سازگاری بعضی کانفیگ‌های XHTTP و Cloudflare با ALPN `h2`
- اصلاح نمایش شماره نسخه در بخش «درباره برنامه»
- افزودن گزینه «بررسی آپدیت» برای نسخه‌های منتشرشده در GitHub Releases
- حفظ شناسه برنامه و امضای نسخه‌های سازگار برای نصب به‌صورت به‌روزرسانی

**سیستم‌عامل:** Android 8 به بالا  
**فایل نصب:** `KingVPN-v0.3.3.apk`

## 🇬🇧 What's new
- Improved XHTTP/CDN ALPN compatibility for configurations supporting `h2`
- Fixed About screen version label
- Added official GitHub Releases update checking with Android installation confirmation
- Signed Android APK, intended as an in-place upgrade where signatures match

**Note:** Connection compatibility varies by configuration. This build passed CI compilation, but successful installation and real-device connectivity should be verified before calling it stable.

**Security:** Install only the APK attached to the official KingServer Release. Never share private configs, UUIDs or signing files.

© KingServer.
