---
title: "الفئة EmfPlusPathPointTypeRle"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathPointTypeRle. كائن EmfPlusPathPointTypeRle يحدد قيم النوع المرتبطة بالنقاط على مسار رسومي باستخدام ضغط RLE. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B1RunCount  PointType  B 1 بت إذا تم تعيينه تكون نقاط المسار على منحنى بيزيير. إذا لم يتم تعيينه تكون نقاط المسار على خط رسومي. RunCount 6 بت عدد التشغيل وهو عدد نقاط المسار التي ترتبط بالنوع في حقل PointType. PointType 1 بايت كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار"
type: docs
weight: 5770
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
## EmfPlusPathPointTypeRle class

كائن EmfPlusPathPointTypeRle يحدد قيم النوع المرتبطة بالنقاط على مسار رسومي باستخدام ضغط RLE. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B&#x7C;1&#x7C;RunCount &#x7C; PointType &#x7C; B (1 بت): إذا تم تعيينه، تكون نقاط المسار على منحنى بيزيير. إذا لم يُحدد، تكون نقاط المسار على خط رسومي. RunCount (6 بت): عدد المتتالية، وهو عدد نقاط المسار التي يجب ربطها بالنوع في حقل PointType. PointType (1 بايت): كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار.

```csharp
public sealed class EmfPlusPathPointTypeRle : EmfPlusBasePointType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusPathPointTypeRle](emfpluspathpointtyperle/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bezier](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/bezier/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `EmfPlusPathPointTypeRle` بيزيير. إذا تم تعيينها، تكون نقاط المسار على منحنى بيزيير. إذا لم يتم تعيينها، تكون نقاط المسار على خط رسومي. |
| [Data](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/data/) { get; set; } | يسترجع أو يعيّن البيانات. |
| [PointType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/pointtype/) { get; set; } | يحصل أو يضبط نوع النقطة. PointType (1 بايت): كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار. |
| [RunCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/runcount/) { get; set; } | يحصل أو يضبط عدد التشغيل. RunCount (6 بت): عدد التشغيل، وهو عدد نقاط المسار التي سيتم ربطها بالنوع في حقل PointType. |

### انظر أيضًا

* class [EmfPlusBasePointType](../emfplusbasepointtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


