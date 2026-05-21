---
title: "EmfPlusPixelFormat"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد PixelFormat صيغ البكسل المدعومة في صور EMF."
type: docs
weight: 43
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

تحدد تعداد PixelFormat صيغ البكسل المدعومة في صور EMF+ النقطية.
## الحقول

| حقل | الوصف |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | لم يتم تحديد الصيغة. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | الصيغة أحادية اللون، ويتم استخدام جدول بحث لوحة ألوان. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | الصيغة ذات 16 لونًا، ويتم استخدام جدول بحث لوحة ألوان. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | الصيغة ذات 256 لونًا، ويتم استخدام جدول بحث لوحة ألوان. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | الصيغة 16 بت لكل بكسل، تدرج رمادي. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | الصيغة 16 بت لكل بكسل؛ تُستخدم 5 بت لكل من مكوّنات الأحمر والأخضر والأزرق. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | الصيغة 16 بت لكل بكسل؛ تُستخدم 5 بت للمكوّن الأحمر، 6 بت للمكوّن الأخضر، و5 بت للمكوّن الأزرق. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | الصيغة 16 بت لكل بكسل؛ تُستخدم بت واحد للمكوّن ألفا، و5 بت لكل من مكوّنات الأحمر والأخضر والأزرق. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | الصيغة 24 بت لكل بكسل؛ تُستخدم 8 بت لكل من مكوّنات الأحمر والأخضر والأزرق. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | الصيغة 32 بت لكل بكسل؛ تُستخدم 8 بت لكل من مكوّنات الأحمر والأخضر والأزرق. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | الصيغة 32 بت لكل بكسل؛ تُستخدم 8 بت لكل من مكوّنات ألفا، الأحمر، الأخضر، والأزرق. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | الصيغة 32 بت لكل بكسل؛ تُستخدم 8 بت لكل من مكوّنات ألفا، الأحمر، الأخضر، والأزرق. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | الصيغة 48 بت لكل بكسل؛ تُستخدم 16 بت لكل من مكوّنات الأحمر والأخضر والأزرق. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | الصيغة 64 بت لكل بكسل؛ تُستخدم 16 بت لكل من مكوّنات ألفا، الأحمر، الأخضر، والأزرق. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | الصيغة 64 بت لكل بكسل؛ تُستخدم 16 بت لكل من مكوّنات ألفا، الأحمر، الأخضر، والأزرق. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


لم يتم تحديد الصيغة.

--------------------

يتم تحديد صيغ البكسل بواسطة كائنات [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap). يتم ترميزها كما يلي: - البتات 0-7: تعداد ثوابت صيغة البكسل، يبدأ من الصفر. - البتات 8-15: إجمالي عدد البتات لكل بكسل. - البت 16: إذا تم تعيينه، يتم فهرسة قيمة اللون في لوحة ألوان. - البت 17: إذا تم تعيينه، تكون قيمة اللون بتنسيق مدعوم من GDI. - البت 18: إذا تم تعيينه، تحتوي قيمة اللون على مكوّن ألفا. - البت 19: إذا تم تعيينه، تحتوي قيمة اللون على مكوّن ألفا مضاعف مسبقًا. - البت 20: إذا تم تعيينه، يتم دعم الألوان الموسعة، 16 بت لكل قناة. - البتات 21-31: محجوزة.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


الصيغة أحادية اللون، ويتم استخدام جدول بحث لوحة ألوان.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


الصيغة ذات 16 لونًا، ويتم استخدام جدول بحث لوحة ألوان.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


الصيغة ذات 256 لونًا، ويتم استخدام جدول بحث لوحة ألوان.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


الصيغة 16 بت لكل بكسل، تدرج رمادي.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


الصيغة 16 بت لكل بكسل؛ تُستخدم 5 بت لكل من مكوّنات الأحمر والأخضر والأزرق. البت المتبقي غير مستخدم.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


الصيغة 16 بت لكل بكسل؛ تُستخدم 5 بت للمكوّن الأحمر، 6 بت للمكوّن الأخضر، و5 بت للمكوّن الأزرق.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


الصيغة 16 بت لكل بكسل؛ تُستخدم بت واحد للمكوّن ألفا، و5 بت لكل من مكوّنات الأحمر والأخضر والأزرق.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


الصيغة 24 بت لكل بكسل؛ تُستخدم 8 بت لكل من مكوّنات الأحمر والأخضر والأزرق.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


الصيغة 32 بت لكل بكسل؛ تُستخدم 8 بت لكل من مكوّنات الأحمر والأخضر والأزرق. الـ 8 بت المتبقية غير مستخدمة.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


الصيغة 32 بت لكل بكسل؛ تُستخدم 8 بت لكل من مكوّنات ألفا، الأحمر، الأخضر، والأزرق.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


الصيغة 32 بت لكل بكسل؛ تُستخدم 8 بت لكل من مكوّنات ألفا، الأحمر، الأخضر، والأزرق. مكوّنات الأحمر والأخضر والأزرق مضاعفة مسبقًا وفقًا لمكوّن ألفا.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


الصيغة 48 بت لكل بكسل؛ تُستخدم 16 بت لكل من مكوّنات الأحمر والأخضر والأزرق.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


الصيغة 64 بت لكل بكسل؛ تُستخدم 16 بت لكل من مكوّنات ألفا، الأحمر، الأخضر، والأزرق.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


الصيغة 64 بت لكل بكسل؛ تُستخدم 16 بت لكل من مكوّنات ألفا، الأحمر، الأخضر، والأزرق. مكوّنات الأحمر والأخضر والأزرق مضاعفة مسبقًا وفقًا لمكوّن ألفا.

