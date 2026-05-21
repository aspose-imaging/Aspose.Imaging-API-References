---
title: "الفئة EmfPlusLanguageIdentifier"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLanguageIdentifier. يحدد كائن EmfPlusLanguageIdentifier معرف لغة يتطابق مع اللغة الطبيعية في إعداد إقليمي يشمل الدول والمناطق الجغرافية والمناطق الإدارية. كل معرف لغة هو ترميز لقيمة اللغة الأساسية وقيمة اللغة الفرعية."
type: docs
weight: 5650
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
## EmfPlusLanguageIdentifier class

كائن EmfPlusLanguageIdentifier يحدد معرف لغة يتطابق مع اللغة الطبيعية في الإعداد المحلي، بما في ذلك البلدان، المناطق الجغرافية، والدوائر الإدارية. كل معرف لغة هو ترميز لقيمة اللغة الأساسية وقيمة اللغة الفرعية.

```csharp
public sealed class EmfPlusLanguageIdentifier : EmfPlusStructureObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusLanguageIdentifier](emfpluslanguageidentifier/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Value](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/value/) { get; set; } | يحصل أو يعيّن قيمة الحقل 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId&#x7C; PrimaryLanguageId &#x7C; SubLanguageId (6 بت): الدولة أو المنطقة الجغرافية أو المنطقة الإدارية للغة الطبيعية المحددة في حقل PrimaryLanguageId. معرفات اللغة الفرعية قابلة للتوسيع من قبل البائع. يجب أن تكون معرفات اللغة الفرعية المعرفة من قبل البائع في النطاق 0x20 إلى 0x3F، شاملة. PrimaryLanguageId (10 بت): اللغة الطبيعية. معرفات اللغة الأساسية قابلة للتوسيع من قبل البائع. يجب أن تكون معرفات اللغة الأساسية المعرفة من قبل البائع في النطاق 0x0200 إلى 0x03FF، شاملة. |

### انظر أيضًا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


