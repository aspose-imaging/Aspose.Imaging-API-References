---
title: "تعداد EmfPlusPathPointFlags"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPathPointFlags. عدد صحيح غير موقع 32 بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي يعرفها هذا الكائن. C بت واحد إذا تم تعيينه، يحدد مصفوفة PathPoints مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16 بت. إذا لم يتم تعيينه، يحدد مصفوفة PathPoints مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32 بت. ملاحظة: إذا تم تعيين علم P أدناه قد يكون هذا العلم غير معين ويجب تجاهله. R بت واحد إذا تم تعيينه، يتم تحديد أنواع النقاط في مصفوفة PathPointTypes بواسطة كائنات EmfPlusPathPointTypeRle القسم 2.2.2.32 التي تستخدم ترميز طول التشغيل RLE وضغط و/أو كائنات EmfPlusPathPointType القسم 2.2.2.31. راجع قسم MSWMF 3.1.6 لمزيد من المعلومات حول ضغط RLE. إذا لم يتم تعيينه، يتم تحديد أنواع النقاط في مصفوفة PathPointTypes بواسطة كائنات EmfPlusPathPointType. P بت واحد إذا تم تعيينه، كل عنصر في مصفوفة PathPoints يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PathPoints يُفترض وجود موقع سابق عند الإحداثيات 00. إذا لم يتم تعيينه، كل عنصر في مصفوفة PathPoints يحدد موقعًا مطلقًا."
type: docs
weight: 5080
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
## EmfPlusPathPointFlags enumeration

عدد صحيح غير موقع 32 بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي يحددها هذا الكائن. C (بت واحد): إذا تم تعيينه، فإن مصفوفة PathPoints تحدد مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16 بت. إذا لم يتم تعيينه، فإن مصفوفة PathPoints تحدد مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32 بت. ملاحظة: إذا تم تعيين علم P (أدناه)، قد يكون هذا العلم غير مُعين ويجب تجاهله. R (بت واحد): إذا تم تعيينه، فإن أنواع النقاط في مصفوفة PathPointTypes تُحدد بواسطة كائنات EmfPlusPathPointTypeRle (القسم 2.2.2.32)، التي تستخدم ضغط الترميز بطول المتسلسلة (RLE)، و/أو كائنات EmfPlusPathPointType (القسم 2.2.2.31). راجع قسم [MS-WMF] 3.1.6 لمزيد من المعلومات حول ضغط RLE. إذا لم يتم تعيينه، فإن أنواع النقاط في مصفوفة PathPointTypes تُحدد بواسطة كائنات EmfPlusPathPointType. P (بت واحد): إذا تم تعيينه، فإن كل عنصر في مصفوفة PathPoints يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PathPoints، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم تعيينه، فإن كل عنصر في مصفوفة PathPoints يحدد موقعًا مطلقًا.

```csharp
[Flags]
public enum EmfPlusPathPointFlags : short
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| C | `4000` | العلم c |
| R | `1000` | العلم r |
| P | `800` | العلم p |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


