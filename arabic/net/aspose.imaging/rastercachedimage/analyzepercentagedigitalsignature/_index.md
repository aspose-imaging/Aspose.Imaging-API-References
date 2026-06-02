---
title: "RasterCachedImage.AnalyzePercentageDigitalSignature"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية."
type: docs
weight: 50
url: /ar/net/aspose.imaging/rastercachedimage/analyzepercentagedigitalsignature/
---
## RasterCachedImage.AnalyzePercentageDigitalSignature method

يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية.

```csharp
public override int AnalyzePercentageDigitalSignature(string password)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | String | كلمة المرور المستخدمة لاستخراج البيانات المدمجة. |

### قيمة الإرجاع

قيمة نسبة التشابه.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | يُطرح في حال حدوث أي مشكلات في المعالجة. |

## أمثلة

يوضح المثال كيفية تحديد الاحتمال (من 0% إلى 100%) أن تحتوي الصورة على توقيع رقمي تم إنشاؤه باستخدام كلمة المرور المحددة.

```csharp
[C#]

using (var image = Image.Load(outputPath))
{
    var signedPercentage = image.AnalyzePercentageDigitalSignature(password);
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


