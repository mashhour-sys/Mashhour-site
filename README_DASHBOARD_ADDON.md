# إضافة لوحة مؤشرات – جاهزة
- API: /api/metrics/summary, /api/metrics/risk-trend, /api/metrics/domain-share
- واجهة: Dashboard.jsx (مخططات Canvas خفيفة)
- SQL Views اختيارية، وMetabase كخيار BI بدون كود

## الدمج
- انسخ MetricsController.java إلى backend ثم أعد تشغيل الـAPI
- انسخ Dashboard.jsx إلى frontend/src وعدّل App.jsx حسب App_PATCH_INSTRUCTIONS.js
- (اختياري) شغل Metabase للتحليل الحر
