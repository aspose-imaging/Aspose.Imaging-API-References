---
title: "الفئة EmfLogBrushEx"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx. كائن LogBrushEx يحدد نمط اللون والنمط لفرشاة مستقلة عن الجهاز."
type: docs
weight: 3110
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
## EmfLogBrushEx class

كائن LogBrushEx يحدد النمط واللون والنقشة لفرشاة مستقلة عن الجهاز.

```csharp
public sealed class EmfLogBrushEx : EmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfLogBrushEx](emflogbrushex/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/argb32colorref/) { get; set; } | يحصل أو يعيّن كائن WMF ColorRef 32 بت ([MS-WMF] القسم 2.2.2.8) يحدد لونًا. يعتمد تفسير هذا الحقل على قيمة BrushStyle، كما هو موضح في الجدول التالي. |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/brushhatch/) { get; set; } | يحصل أو يعيّن حقلًا غير موقع 32 بت يحتوي على بيانات نمط الفرشاة. تفسيره يعتمد على قيمة BrushStyle، |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/brushstyle/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد نمط الفرشاة. يجب أن تكون القيمة تعدادًا من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). قيم الأنماط المدعومة في هذه البنية مُدرجة لاحقًا في هذا القسم. يجب استخدام النمط BS_NULL لتحديد فرشاة ليس لها تأثير. |

### انظر أيضًا

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


