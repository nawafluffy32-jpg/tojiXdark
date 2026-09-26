# Violet Network

<p>
	<a href="http://localhost:3000/" target="_blank" rel="noreferrer" aria-label="افتح موقع Violet Network" style="display:inline-flex;align-items:center;gap:8px;padding:8px 12px;background:#d62839;border-radius:4px;color:#fff;text-decoration:none;font-weight:700">
		<span aria-hidden="true">X</span>
		<span>افتح الموقع</span>
	</a>
</p>

## تسجيل دخول ماينكرافت

الدخول يصير باسم اللاعب فقط، من 3 إلى 16 حرف أو رقم. الاسم مو متحقق منه من Mojang أو Microsoft، فممكن أي لاعب ينتحل اسم غيره. لا تعتمد عليه لصلاحيات الإدارة أو المشتريات أو إثبات ملكية الحساب.

الجلسات تنحفظ بكوكيز `HttpOnly`، وبيانات اللاعبين تنحفظ افتراضيًا بقاعدة SQLite داخل `data/violet.sqlite`. انتبه: قرص Vercel مؤقت، فقاعدة SQLite المحلية ما تضمن بقاء الحسابات بعد إعادة تشغيل التطبيق. قبل الاعتماد على تسجيل الدخول بالنشر، اربطه بقاعدة بيانات مستضافة ودائمة.

للتشغيل محليًا: `npm install` وبعدها `npm run dev`.
