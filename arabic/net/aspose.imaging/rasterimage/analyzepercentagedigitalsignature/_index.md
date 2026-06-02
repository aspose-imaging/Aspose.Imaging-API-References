---
title: "RasterImage.AnalyzePercentageDigitalSignature"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية"
type: docs
weight: 210
url: /ar/net/aspose.imaging/rasterimage/analyzepercentagedigitalsignature/
---
## RasterImage.AnalyzePercentageDigitalSignature method

يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية.

```csharp
public virtual int AnalyzePercentageDigitalSignature(string password)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | String | كلمة المرور المستخدمة لاستخراج البيانات المدمجة. |

### قيمة الإرجاع

قيمة نسبة التشابه.

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

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


