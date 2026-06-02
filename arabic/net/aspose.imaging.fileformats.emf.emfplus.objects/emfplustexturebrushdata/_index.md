---
title: "الفئة EmfPlusTextureBrushData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusTextureBrushData. يحدد كائن EmfPlusTextureBrushData صورة نسيج لفرشاة رسومية."
type: docs
weight: 5930
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
## EmfPlusTextureBrushData class

كائن EmfPlusTextureBrushData يحدد صورة نسيجية لفرشاة رسومية.

```csharp
public sealed class EmfPlusTextureBrushData : EmfPlusBaseBrushData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusTextureBrushData](emfplustexturebrushdata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/brushdataflags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد البيانات في حقل OptionalData. يجب أن تتكون هذه القيمة من أعلام BrushData (القسم 2.1.2.1). الأعلام التالية ذات صلة بفرشاة النسيج BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform. |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/optionaldata/) { get; set; } | يحصل أو يعيّن كائن EmfPlusTextureBrushOptionalData اختياري (القسم 2.2.2.46) يحدد بيانات إضافية لفرشاة النسيج. يتم تحديد المحتويات المحددة لهذا الحقل بقيمة حقل BrushDataFlags. |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/wrapmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت من تعداد WrapMode (القسم 2.1.1.34) يحدد كيفية تكرار صورة النسيج عبر الشكل عندما تكون الصورة أصغر من المنطقة التي يتم ملؤها. |

### انظر أيضًا

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


