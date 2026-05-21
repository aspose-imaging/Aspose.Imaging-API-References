---
title: "RasterCachedImage.AutoBrightnessContrast"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تقوم بأداء تعديل تلقائي متكيف للسطوع والتباين عبر تطبيع كامل الصورة."
type: docs
weight: 60
url: /ar/net/aspose.imaging/rastercachedimage/autobrightnesscontrast/
---
## RasterCachedImage.AutoBrightnessContrast method

ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها.

```csharp
public override void AutoBrightnessContrast()
```

## ملاحظات

تطبق هذه الطريقة سلسلة من المرشحات المتكيفة المتقدمة (CLAHE، التمدد الأبيض المتكيف، وتوازن اللون الأبيض التلقائي) لتحسين الجودة البصرية للصورة عن طريق تعزيز التباين والسطوع المحلي ودقة الألوان.

**Filter pipeline:**

1. تعديل التباين المحدود للهيستوجرام المتكيف (CLAHE) – يحسّن التباين المحلي ويعزز التفاصيل الخفيفة.
2. التمدد الأبيض المتكيف – يزيد من مستوى الأبيض الفعّال مع الحفاظ على الخصائص الداكنة.
3. توازن اللون الأبيض التلقائي – يصحّح الانحرافات اللونية عن طريق موازنة هيستوجرامات القنوات.

**Note:**

* Each filter stage uses its default settings. For custom parameters, apply filters individually.
* The method is intended for use in automated normalization scenarios (e.g., scan preprocessing, document pipelines).

## أمثلة

```csharp
// مثال على الاستخدام في ما قبل معالجة الصورة:
image.AutoBrightnessContrast();
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


