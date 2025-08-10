
# Steps Player 

ملفّان أساسيان:
- `index.html` — صفحة المشاهدة (Player). تقرأ الإعدادات من LocalStorage.
- `admin.html` — لوحة التحكّم محميّة بكلمة مرور (Front-End).

## النشر
ارفع المجلد كما هو لأي استضافة static (Netlify, Vercel, GitHub Pages, S3, Nginx/Apache).
يجب أن تكون `index.html` و `admin.html` على نفس الدومين ليشتركوا في LocalStorage.

## الاستخدام
1) افتح `admin.html` أول مرة لتعيين كلمة مرور.
2) عدّل الإعدادات واحفظ.
3) افتح/حدّث `index.html` لمشاهدة التغييرات.

