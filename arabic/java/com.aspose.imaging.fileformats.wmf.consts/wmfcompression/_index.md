---
title: "WmfCompression"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "التعداد Compression يحدد نوع الضغط لصورة bitmap."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

التعداد Compression يحدد نوع الضغط لصورة bitmap.
## الحقول

| حقل | الوصف |
| --- | --- |
| [BI_RGB](#BI-RGB) | الصورة النقطية بتنسيق الأحمر الأخضر الأزرق (RGB) غير مضغوطة ولا تستخدم أقنعة ألوان. |
| [BI_RLE8](#BI-RLE8) | تنسيق RGB يستخدم ضغط ترميز الطول المتسلسل (RLE) للصور النقطية ذات 8 بت لكل بكسل. |
| [BI_RLE4](#BI-RLE4) | تنسيق RGB يستخدم ضغط RLE للصور النقطية ذات 4 بت لكل بكسل. |
| [BI_BITFIELDS](#BI-BITFIELDS) | الصورة النقطية غير مضغوطة وجدول الألوان يتكون من ثلاث أقنعة لون DWORD تحدد المكونات الحمراء والخضراء والزرقاء، على التوالي، لكل بكسل. |
| [BI_JPEG](#BI-JPEG) | الصورة هي صورة JPEG، كما هو موضح في [JFIF]. |
| [BI_PNG](#BI-PNG) | الصورة هي صورة PNG، كما هو موضح في [RFC2083]. |
| [BI_CMYK](#BI-CMYK) | الصورة هي تنسيق CMYK غير مضغوط. |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | تنسيق CMYK يستخدم ضغط RLE للصور النقطية ذات 8 بت لكل بكسل. |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | تنسيق CMYK يستخدم ضغط RLE للصور النقطية ذات 4 بت لكل بكسل. |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


الصورة النقطية بتنسيق الأحمر الأخضر الأزرق (RGB) غير مضغوطة ولا تستخدم أقنعة ألوان.

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


تنسيق RGB يستخدم ترميز الطول المتسلسل (RLE) للضغط للصور النقطية ذات 8 بت لكل بكسل. يستخدم الضغط تنسيقًا من 2 بايت يتكون من بايت عدّ يليه بايت يحتوي على فهرس اللون.

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


تنسيق RGB يستخدم ضغط RLE للصور النقطية ذات 4 بت لكل بكسل. يستخدم الضغط تنسيقًا من 2 بايت يتكون من بايت عدّ يليه فهرسان للون بطول كلمة.

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


الصورة النقطية غير مضغوطة وجدول الألوان يتكون من ثلاث أقنعة لون DWORD تحدد المكونات الحمراء والخضراء والزرقاء، على التوالي، لكل بكسل. هذا صالح عند الاستخدام مع صور نقطية ذات 16 و32 بت لكل بكسل.

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


الصورة هي صورة JPEG، كما هو موضح في [JFIF]. يجب أن تُستخدم هذه القيمة فقط في عمليات معينة على الصور النقطية، مثل تمرير JPEG. يجب على التطبيق الاستعلام عن دعم التمرير، لأن ليس كل الأجهزة تدعم تمرير JPEG. قد يؤدي استخدام الصور النقطية غير RGB إلى تقليل قابلية نقل ملف الميتا إلى أجهزة أخرى. على سبيل المثال، سياقات أجهزة العرض عادة لا تدعم هذا التمرير.

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


الصورة هي صورة PNG، كما هو موضح في [RFC2083]. يجب أن تُستخدم هذه القيمة فقط في عمليات معينة على الصور النقطية، مثل تمرير JPEG/PNG. يجب على التطبيق الاستعلام عن دعم التمرير، لأن ليس كل الأجهزة تدعم تمرير JPEG/PNG. قد يؤدي استخدام الصور النقطية غير RGB إلى تقليل قابلية نقل ملف الميتا إلى أجهزة أخرى. على سبيل المثال، سياقات أجهزة العرض عادة لا تدعم هذا التمرير.

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


الصورة هي تنسيق CMYK غير مضغوط.

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


تنسيق CMYK يستخدم ضغط RLE للصور النقطية ذات 8 بت لكل بكسل. يستخدم الضغط تنسيقًا من 2 بايت يتكون من بايت عدّ يليه بايت يحتوي على فهرس اللون.

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


تنسيق CMYK يستخدم ضغط RLE للصور النقطية ذات 4 بت لكل بكسل. يستخدم الضغط تنسيقًا من 2 بايت يتكون من بايت عدّ يليه فهرسان للون بطول كلمة.

