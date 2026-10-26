# موقع الشركة — work-1

صفحة شركة عربية/إنجليزية بسيطة. اسم الشركة مؤقت، ومناطق الصفحات فارغة عمدًا لحين إضافة المحتوى لاحقًا.

## الملفات
- `index.html`: الموقع.
- `wrangler.jsonc`: إعداد نشر الملفات الثابتة على Cloudflare Workers.
- `.assetsignore`: يمنع نشر ملفات الإعدادات وREADME ضمن ملفات الموقع العامة.

## ربط المستودع بـ Cloudflare

### إنشاء Worker جديد من GitHub
1. افتح لوحة Cloudflare: https://dash.cloudflare.com/
2. ادخل إلى **Workers & Pages** ثم **Create application**.
3. اختر **GitHub** واربط حساب GitHub إذا طُلب منك ذلك.
4. اختر المستودع `bassamsaif0000/work-1`.
5. اختر **Save and Deploy**.
6. بعد النشر ستظهر وصلة `workers.dev` الخاصة بالموقع.

### ربط Worker موجود
من **Workers & Pages** افتح الـ Worker المقصود ثم **Settings → Builds → Connect**، واختر مستودع `work-1`. يجب أن يتطابق اسم الـ Worker في Cloudflare مع قيمة `name` في `wrangler.jsonc` (حاليًا `work-1`). بعد الربط، تُنشر التغييرات تلقائيًا عند دفع تحديثات إلى GitHub.

لا توجد صور أو نصوص تعريفية أو بيانات اتصال إضافية في الصفحة حاليًا، باستثناء الروابط العلوية وحقوق النشر.
