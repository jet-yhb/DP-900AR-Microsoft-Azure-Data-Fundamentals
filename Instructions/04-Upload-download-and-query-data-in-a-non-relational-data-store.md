﻿Lab:
   title: 'تحميل البيانات وتنزيلها والاستعلام عنها في مخزن بيانات غير ارتباطية'
---

## الإرشادات
في سيناريو العينة، افترض أنك أنشأت مخازن البيانات التالية:

قاعدة بيانات Cosmos DB للاحتفاظ بمعلومات حول المنتجات التي تصنعها شركة Contoso.
حاوية بيانات ثنائية كبيرة الحجم في Azure Storage للاحتفاظ بصور المنتجات.
مشاركة ملف، في نفس حساب Azure Storage، للاحتفاظ بوثائق المنتج.
في هذا التمرين، ستقوم بتحميل البيانات إلى مخازن البيانات هذه. ستقوم بتشغيل استعلامات مقابل البيانات الموجودة في قاعدة بيانات Cosmos DB. أخيرًا، ستقوم بتنزيل الصور والمستندات الموجودة في Azure Storage وعرضها.

ستقوم بإجراء هذا التمرين باستخدام مدخل Azure وسطر الأوامر.

1.	انتقل إلى تمرين Microsoft Learn على https://docs.microsoft.com/learn/modules/explore-non-relational-data-stores-azure/6-exercise وأكمل الوحدة في المتصفح: 