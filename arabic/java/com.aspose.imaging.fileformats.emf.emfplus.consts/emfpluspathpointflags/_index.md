---
title: "EmfPlusPathPointFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي يعرفها هذا الكائن."
type: docs
weight: 38
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي تم تعريفها بواسطة هذا الكائن. C (بت واحد): إذا تم تعيينه، فإن مصفوفة PathPoints تحدد مواقع مطلقة في فضاء الإحداثيات بإحداثيات صحيحة 16‑بت. إذا لم يتم تعيينه، فإن مصفوفة PathPoints تحدد مواقع مطلقة في فضاء الإحداثيات بإحداثيات عائمة 32‑بت. ملاحظة إذا تم تعيين علامة P (أدناه)، قد تكون هذه العلامة غير مفعلة ويجب تجاهلها. R (بت واحد): إذا تم تعيينه، فإن أنواع النقاط في مصفوفة PathPointTypes يتم تحديدها بواسطة كائنات EmfPlusPathPointTypeRle (القسم 2.2.2.32)، التي تستخدم ضغط الترميز بطول المتسلسلة (RLE)، و/أو كائنات EmfPlusPathPointType (القسم 2.2.2.31). راجع [MS-WMF] القسم 3.1.6 لمزيد من المعلومات حول ضغط RLE. إذا لم يتم تعيينه، فإن أنواع النقاط في مصفوفة PathPointTypes يتم تحديدها بواسطة كائنات EmfPlusPathPointType. P (بت واحد): إذا تم تعيينه، كل عنصر في مصفوفة PathPoints يحدد موقعًا في فضاء الإحداثيات يكون نسبياً إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PathPoints، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم تعيينه، كل عنصر في مصفوفة PathPoints يحدد موقعًا مطلقًا.
## الحقول

| حقل | الوصف |
| --- | --- |
| [C](#C) | علامة c |
| [R](#R) | علامة r |
| [P](#P) | علامة p |
### C {#C}
```
public static final short C
```


علامة c

### R {#R}
```
public static final short R
```


علامة r

### P {#P}
```
public static final short P
```


علامة p

