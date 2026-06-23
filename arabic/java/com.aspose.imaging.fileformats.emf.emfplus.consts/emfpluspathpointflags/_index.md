---
title: "EmfPlusPathPointFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "عدد صحيح غير موقع 32-بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي يعرفها هذا الكائن."
type: docs
weight: 38
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي يعرفها هذا الكائن. C (1 بت): إذا تم تعيينه، تحدد مصفوفة PathPoints مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا تم إلغاء التعيين، تحدد مصفوفة PathPoints مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة إذا تم تعيين علم P (أدناه)، قد يكون هذا العلم غير مفعّل ويجب تجاهله. R (1 بت): إذا تم تعيينه، يتم تحديد أنواع النقاط في مصفوفة PathPointTypes بواسطة كائنات EmfPlusPathPointTypeRle (القسم 2.2.2.32)، التي تستخدم ضغط الترميز بطول المتسلسلة (RLE)، و/أو كائنات EmfPlusPathPointType (القسم 2.2.2.31). راجع [MS-WMF] القسم 3.1.6 لمزيد من المعلومات حول ضغط RLE. إذا تم إلغاء التعيين، يتم تحديد أنواع النقاط في مصفوفة PathPointTypes بواسطة كائنات EmfPlusPathPointType. P (1 بت): إذا تم تعيينه، يحدد كل عنصر في مصفوفة PathPoints موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PathPoints، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم إلغاء التعيين، يحدد كل عنصر في مصفوفة PathPoints موقعًا مطلقًا.
## الحقول

| حقل | الوصف |
| --- | --- |
| [C](#C) | العلم c |
| [R](#R) | العلم r |
| [P](#P) | العلم p |
### C {#C}
```
public static final short C
```


العلم c

### R {#R}
```
public static final short R
```


العلم r

### P {#P}
```
public static final short P
```


العلم p

