---
title: "DibBitCount"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد BitCount عدد البتات التي تحدد كل بكسل والحد الأقصى لعدد الألوان في صورة bitmap مستقلة عن الجهاز DIB."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

تحدد تعداد BitCount عدد البتات التي تُعرف كل بكسل والحد الأقصى لعدد الألوان في bitmap مستقل عن الجهاز (DIB).
## الحقول

| حقل | الوصف |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | عدد البتات لكل بكسل غير معرف. |
| [BIT_COUNT_1](#BIT-COUNT-1) | تم تحديد الصورة بلونين. كل بكسل في الـ bitmap يُمثَّل ببت واحد. |
| [BIT_COUNT_2](#BIT-COUNT-2) | تم تحديد الصورة بحد أقصى 16 لونًا. |
| [BIT_COUNT_3](#BIT-COUNT-3) | تم تحديد الصورة بحد أقصى 256 لونًا. |
| [BIT_COUNT_4](#BIT-COUNT-4) | تم تحديد الصورة بحد أقصى 2^16 لونًا. |
| [BIT_COUNT_5](#BIT-COUNT-5) | يحتوي الـ bitmap على حد أقصى 2^24 لونًا، وحقل Colors في DIB هو NULL. |
| [BIT_COUNT_6](#BIT-COUNT-6) | يحتوي الـ bitmap على حد أقصى 2^24 لونًا |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


عدد البتات لكل بكسل غير معرف. يجب أن تكون الصورة إما بتنسيق JPEG أو PNG. لا يتضمن أي من هذين التنسيقين جدول ألوان، لذا تُشير هذه القيمة إلى عدم وجود جدول ألوان. راجع [JFIF] و [RFC2083] لمزيد من المعلومات حول صيغ ضغط JPEG و PNG.

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


تم تحديد الصورة بلونين. كل بكسل في الـ bitmap يُمثَّل ببت واحد. إذا كان البت مُصفَّرًا، يُعرض البكسل بلون الإدخال الأول في جدول الألوان؛ إذا كان البت مُضبطًا، يكون لون البكسل هو اللون الثاني في الجدول.

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


تم تحديد الصورة بحد أقصى 16 لونًا. كل بكسل في الـ bitmap يُمثَّل بفهرس 4-بت في جدول الألوان، وكل بايت يحتوي على بكسلين.

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


تم تحديد الصورة بحد أقصى 256 لونًا. كل بكسل في الـ bitmap يُمثَّل بفهرس 8-بت في جدول الألوان، وكل بايت يحتوي على بكسل واحد.

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


تم تحديد الصورة بحد أقصى 2^16 لونًا. كل بكسل في الـ bitmap يُمثَّل بقيمة 16-بت

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


يحتوي الـ bitmap على حد أقصى 2^24 لونًا، وحقل Colors في DIB هو NULL. كل مجموعة ثلاثية بايت في مصفوفة الـ bitmap تمثل شدة اللون الأزرق والأخضر والأحمر نسبياً لكل بكسل. يُستخدم جدول ألوان Colors لتحسين الألوان المستخدمة على الأجهزة القائمة على اللوحات، ويجب أن يحتوي على عدد الإدخالات المحدد بحقل ColorUsed في كائن BitmapInfoHeader Object

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


يحتوي الـ bitmap على حد أقصى 2^24 لونًا

