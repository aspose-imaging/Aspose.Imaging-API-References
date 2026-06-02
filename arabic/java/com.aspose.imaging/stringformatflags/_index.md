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
| [FitBlackBox](#FitBlackBox) | يسمح لأجزاء الأحرف أن تتجاوز مستطيل تخطيط السلسلة. |
| [DisplayFormatControl](#DisplayFormatControl) | يتم إظهار أحرف التحكم مثل علامة اليسار إلى اليمين في المخرجات برمز تمثيلي. |
| [NoFontFallback](#NoFontFallback) | تم تعطيل الانتقال إلى خطوط بديلة للأحرف غير المدعومة في الخط المطلوب. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | يتضمن المسافة المتتبعة في نهاية كل سطر. |
| [NoWrap](#NoWrap) | تغليف النص بين الأسطر عند التنسيق داخل مستطيل تم تعطيله. |
| [LineLimit](#LineLimit) | يتم تنسيق أسطر كاملة فقط داخل مستطيل التنسيق. |
| [NoClip](#NoClip) | يسمح بإظهار الأجزاء المتجاوزة من الرموز، والنص غير المغلف الذي يمتد خارج مستطيل التنسيق. |
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


يسمح لأجزاء الأحرف أن تتجاوز مستطيل تخطيط السلسلة. بشكل افتراضي، يتم إعادة وضع الأحرف لتجنب أي تجاوز.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


يتم إظهار أحرف التحكم مثل علامة اليسار إلى اليمين في المخرجات برمز تمثيلي.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


تم تعطيل الانتقال إلى خطوط بديلة للأحرف غير المدعومة في الخط المطلوب. أي أحرف مفقودة يتم عرضها برمز الخط المفقود، عادةً مربع مفتوح.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


يتضمن المسافة المتتبعة في نهاية كل سطر. بشكل افتراضي، مستطيل الحدود الذي تُرجعه طريقة MeasureString يستثني المسافة في نهاية كل سطر. اضبط هذه العلامة لتضمين تلك المسافة في القياس.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


تغليف النص بين الأسطر عند التنسيق داخل مستطيل تم تعطيله. تُستنتج هذه العلامة عندما يتم تمرير نقطة بدلاً من مستطيل، أو عندما يكون طول الخط في المستطيل المحدد صفرًا.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


يتم تنسيق أسطر كاملة فقط داخل مستطيل التنسيق. بشكل افتراضي يستمر التنسيق حتى نهاية النص، أو حتى لا تصبح هناك أسطر أخرى مرئية نتيجة للقص، أيهما يأتي أولاً. لاحظ أن الإعدادات الافتراضية تسمح بأن يكون السطر الأخير مغطى جزئيًا بمستطيل التنسيق الذي لا يكون مضاعفًا كاملًا لارتفاع السطر. لضمان رؤية أسطر كاملة فقط، حدد هذه القيمة وكن حذرًا في توفير مستطيل تنسيق بطول لا يقل عن ارتفاع سطر واحد.

### NoClip {#NoClip}
```
public static final int NoClip
```


يسمح بإظهار الأجزاء المتجاوزة من الرموز، والنص غير المغلف الذي يمتد خارج مستطيل التنسيق. بشكل افتراضي، يتم قص جميع النصوص وأجزاء الرموز التي تمتد خارج مستطيل التنسيق.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


المحاذاة الدقيقة، الحشو الصحيح GDI+

