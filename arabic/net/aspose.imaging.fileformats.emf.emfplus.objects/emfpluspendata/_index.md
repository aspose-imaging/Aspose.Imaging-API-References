---
title: "الفئة EmfPlusPenData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPenData الفئة. كائن EmfPlusPenData يحدد خصائص قلم رسومي."
type: docs
weight: 5790
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
## EmfPlusPenData class

كائن EmfPlusPenData يحدد خصائص قلم رسومي.

```csharp
public sealed class EmfPlusPenData : EmfPlusStructureObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusPenData](emfpluspendata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/optionaldata/) { get; set; } | الحصول أو تعيين كائن EmfPlusPenOptionalData اختياري (القسم 2.2.2.34) الذي يحدد بيانات إضافية لكائن القلم. المحتويات المحددة لهذا الحقل يتم تحديدها بقيمة حقل PenDataFlags. |
| [PenDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/pendataflags/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد البيانات في حقل OptionalData. يجب أن يتكون هذا القيمة من أعلام PenData (القسم 2.1.2.7). |
| [PenUnit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/penunit/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد وحدات القياس للقلم. يجب أن تكون القيمة من تعداد UnitType (القسم 2.1.1.33). |
| [PenWidth](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/penwidth/) { get; set; } | الحصول أو تعيين قيمة عائمة 32-بت تحدد عرض الخط المرسوم بالقلم بالوحدات المحددة في حقل PenUnit. إذا تم تحديد عرض صفر، يتم استخدام قيمة دنيا يتم تحديدها بحسب الوحدات. |

### انظر أيضًا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


