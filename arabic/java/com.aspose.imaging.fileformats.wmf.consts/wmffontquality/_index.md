---
title: "WmfFontQuality"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعداد FontQuality يحدد مدى تطابق خصائص الخط المنطقي مع خصائص الخط الفعلي عند عرض النص."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

تعداد FontQuality يحدد مدى تطابق خصائص الخط المنطقي مع خصائص الخط الفعلي عند عرض النص.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Default](#Default) | يحدد أن جودة الأحرف للخط غير مهمة، لذا يمكن استخدام DRAFT. |
| [Draft](#Draft) | يحدد أن جودة الأحرف للخط أقل أهمية من مطابقة السمات المنطقية. |
| [Proof](#Proof) | يحدد أن جودة الأحرف للخط أكثر أهمية من مطابقة السمات المنطقية. |
| [Nonantialiased](#Nonantialiased) | يحدد أنه يجب ألا يُستخدم anti-aliasing عند عرض النص |
| [Antialiased](#Antialiased) | يحدد أنه يجب استخدام anti-aliasing عند عرض النص، إذا كان الخط يدعم ذلك. |
| [Cleartype](#Cleartype) | يحدد أنه يجب استخدام ClearType anti-aliasing عند عرض النص، إذا كان الخط يدعم ذلك. |
### Default {#Default}
```
public static final byte Default
```


يحدد أن جودة الأحرف للخط غير مهمة، لذا يمكن استخدام DRAFT.

### Draft {#Draft}
```
public static final byte Draft
```


يحدد أن جودة الأحرف للخط أقل أهمية من مطابقة السمات المنطقية. بالنسبة للخطوط المرسومة، يجب تمكين التحجيم، مما يعني توفر أحجام خطوط أكثر.

### Proof {#Proof}
```
public static final byte Proof
```


يحدد أن جودة الأحرف للخط أكثر أهمية من مطابقة السمات المنطقية. بالنسبة للخطوط المرسومة، يجب تعطيل التحجيم، ويجب اختيار الخط الأقرب في الحجم.

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


يحدد أنه يجب ألا يُستخدم anti-aliasing عند عرض النص

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


يحدد أنه يجب استخدام anti-aliasing عند عرض النص، إذا كان الخط يدعم ذلك.

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


يحدد أنه يجب استخدام ClearType anti-aliasing عند عرض النص، إذا كان الخط يدعم ذلك.

