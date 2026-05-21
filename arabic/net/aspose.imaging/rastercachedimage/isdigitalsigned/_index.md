---
title: "RasterCachedImage.IsDigitalSigned"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تقوم بإجراء فحص سريع لتحديد ما إذا كانت الصورة موقعة رقمياً باستخدام كلمة المرور المقدمة والحدّ."
type: docs
weight: 160
url: /ar/net/aspose.imaging/rastercachedimage/isdigitalsigned/
---
## RasterCachedImage.IsDigitalSigned method

يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والحدّ المحدد.

```csharp
public override bool IsDigitalSigned(string password, int percentageThreshold = -1)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | String | كلمة المرور للتحقق من التوقيع. |
| percentageThreshold | Int32 | الحدّ (بالنسبة المئوية)[0-100] الذي يحدد ما إذا كانت الصورة تعتبر موقعة. إذا لم يتم تحديده، سيتم تطبيق حدّ افتراضي (`75`). |

### قيمة الإرجاع

صحيح إذا كانت الصورة موقعة، وإلا خطأ.

## ملاحظات

توفر هذه الطريقة أسرع كشف عن طريق الاستفادة من !:GetSignPercentage. بمجرد أن تفي البيانات المستخرجة بالحدّ المحدد، يتم تخطي خطوات استخراج إضافية تهدف إلى تحسين دقة الكشف.

## أمثلة

يوضح المثال كيفية التحقق من أن التوقيع الرقمي المدمج يطابق كلمة المرور المقدمة مقابل حدّ الاحتمال المحدد.

```csharp
[C#]

var threshold = 100;
using (var image = Image.Load(outputPath))
{
    var isSigned = image.IsDigitalSigned(password, threshold);
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


