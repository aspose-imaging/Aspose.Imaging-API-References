---
title: "StringFormatFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد معلومات العرض والتخطيط لسلاسل النص."
type: docs
weight: 113
url: /ar/java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

يحدد معلومات العرض والتخطيط لسلاسل النص.
## الحقول

| حقل | الوصف |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | يتم عرض النص من اليمين إلى اليسار. |
| [DirectionVertical](#DirectionVertical) | النص محاذى عموديًا. |
| [FitBlackBox](#FitBlackBox) | مسموح لأجزاء الأحرف أن تتجاوز مستطيل تخطيط السلسلة. |
| [DisplayFormatControl](#DisplayFormatControl) | تُظهر الأحرف التحكمية مثل علامة اليسار إلى اليمين في المخرجات برمز تمثيلي. |
| [NoFontFallback](#NoFontFallback) | تم تعطيل الانتقال إلى خطوط بديلة للأحرف غير المدعومة في الخط المطلوب. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | يتضمن المسافة المتتبعة في نهاية كل سطر. |
| [NoWrap](#NoWrap) | تغليف النص بين الأسطر عند التنسيق داخل مستطيل مُعطل. |
| [LineLimit](#LineLimit) | يتم تنسيق خطوط كاملة فقط داخل مستطيل التنسيق. |
| [NoClip](#NoClip) | مسموح بإظهار أجزاء الحروف المتجاوزة والنص غير المغلف الذي يصل خارج مستطيل التنسيق. |
| [ExactAlignment](#ExactAlignment) | المحاذاة الدقيقة، الحشو الصحيح GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


يتم عرض النص من اليمين إلى اليسار.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


النص محاذى عموديًا.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


مسموح لأجزاء الأحرف أن تتجاوز مستطيل تخطيط السلسلة. بشكل افتراضي، يتم إعادة تموضع الأحرف لتجنب أي تجاوز.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


تُظهر الأحرف التحكمية مثل علامة اليسار إلى اليمين في المخرجات برمز تمثيلي.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


تم تعطيل الانتقال إلى خطوط بديلة للأحرف غير المدعومة في الخط المطلوب. أي أحرف مفقودة تُعرض برمز الخط المفقود، عادةً مربع مفتوح.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


يتضمن المسافة المتتبعة في نهاية كل سطر. بشكل افتراضي، يستبعد مستطيل الحدود الذي تُعيده طريقة MeasureString المسافة في نهاية كل سطر. اضبط هذه العلامة لتضمين تلك المسافة في القياس.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


تغليف النص بين الأسطر عند التنسيق داخل مستطيل مُعطل. تُفترض هذه العلامة عندما يتم تمرير نقطة بدلاً من مستطيل، أو عندما يكون طول الخط للمستطيل المحدد صفرًا.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


يتم تنسيق خطوط كاملة فقط داخل مستطيل التنسيق. بشكل افتراضي، يستمر التنسيق حتى نهاية النص، أو حتى لا تكون هناك خطوط أخرى مرئية نتيجة للقص، أيهما يحدث أولاً. لاحظ أن الإعدادات الافتراضية تسمح للخط الأخير بأن يكون مغطى جزئيًا بمستطيل تنسيق لا يكون مضاعفًا كاملًا لارتفاع السطر. لضمان رؤية خطوط كاملة فقط، حدد هذه القيمة وكن حذرًا في توفير مستطيل تنسيق بطول لا يقل عن ارتفاع سطر واحد.

### NoClip {#NoClip}
```
public static final int NoClip
```


مسموح بإظهار أجزاء الحروف المتجاوزة والنص غير المغلف الذي يصل خارج مستطيل التنسيق. بشكل افتراضي، يتم قص جميع النصوص وأجزاء الحروف التي تصل خارج مستطيل التنسيق.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


المحاذاة الدقيقة، الحشو الصحيح GDI+

