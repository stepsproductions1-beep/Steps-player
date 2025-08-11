
# Multi‑Cam — High‑Security Static Bundle (GitHub Pages Ready)

يوفّر:
- بوابة وصول JWT (RS256) في `index.html`
- إعدادات مشفّرة AES‑GCM (اختياري) أو `config.public.json`
- لوحة تحكّم محمية PBKDF2 في `admin.html`
- أدوات توليد مفاتيح وإصدار Tokens في `tools.html`

## النشر
1) ارفع جميع الملفات لهذا المجلد إلى GitHub.
2) Settings → Pages → Deploy from a branch (main /root).
3) افتح `tools.html` لتوليد `publicKey.json` ورفعها.
4) من `admin.html` عدّل الإعدادات ثم إمّا تصدير `config.public.json` ورفعه، أو حفظ إعدادات مشفّرة في LocalStorage.
5) وزّع الرابط للمشاهدين بصيغة: `https://USERNAME.github.io/REPO/?t=JWT`

ملاحظة: لأمان مؤسسي، استخدم Cloudflare Access على الدومين.
