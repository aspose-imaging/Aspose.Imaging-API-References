---
title: "الفئة EmfPlusPath"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPath الفئة. كائن EmfPlusPath يحدد سلسلة من مقاطع الخط والمنحنى التي تشكل مسار رسومي. ترتيب نقاط بيانات Bezier هو نقطة البداية، نقطة التحكم 1، نقطة التحكم 2، ونقطة النهاية. لمزيد من المعلومات راجع MSDN DrawBeziers."
type: docs
weight: 5730
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
## EmfPlusPath class

كائن EmfPlusPath يحدد سلسلة من المقاطع الخطية والمنحنية التي تشكل مسارًا رسوميًا. ترتيب نقاط بيانات بيزيير هو نقطة البداية، نقطة التحكم 1، نقطة التحكم 2، ونقطة النهاية. لمزيد من المعلومات راجع [MSDN - DrawBeziers].

```csharp
public sealed class EmfPlusPath : EmfPlusGraphicsObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusPath](emfpluspath/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PathPointFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointflags/) { get; set; } | الحصول أو تعيين عدد نقاط المسار عدد صحيح غير موقع 32-بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي يحددها هذا الكائن. |
| [PathPoints](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpoints/) { get; set; } | الحصول أو تعيين مصفوفة من نقاط المسار مصفوفة من نقاط PathPointCount التي تحدد المسار. نوع الكائنات في هذه المصفوفة يحدد بواسطة حقل PathPointFlags، كما يلي: إذا كان علم P مفعلاً، تكون النقاط مواقع نسبية يحددها كائنات EmfPlusPointR (القسم 2.2.2.37). إذا كان علم P غير مفعّل وعلم C مفعلاً، تكون النقاط مواقع مطلقة يحددها كائنات EmfPlusPoint (القسم 2.2.2.35). إذا كان علما P و C غير مفعّلين، تكون النقاط مواقع مطلقة يحددها كائنات EmfPlusPointF (القسم 2.2.2.36). |
| [PathPointTypes](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointtypes/) { get; set; } | الحصول أو تعيين مصفوفة تحدد كيفية استخدام النقاط في حقل PathPoints لرسم المسار. نوع الكائنات في هذه المصفوفة يحدد بواسطة علم R في حقل PathPointFlags. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version/) { get; set; } | الحصول أو تعيين الإصدار. |

### انظر أيضًا

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


