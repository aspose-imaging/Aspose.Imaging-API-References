---
title: "ApngOptions.NumPlays"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية ApngOptions. يحصل أو يضبط عدد مرات تكرار الرسوم المتحركة. 0 تشير إلى تكرار لا نهائي"
type: docs
weight: 30
url: /ar/net/aspose.imaging.imageoptions/apngoptions/numplays/
---
## ApngOptions.NumPlays property

يحصل أو يعيّن عدد مرات تكرار الرسوم المتحركة. 0 تشير إلى تكرار لا نهائي.

```csharp
public int NumPlays { get; set; }
```

### Property Value

عدد مرات التكرار.

## أمثلة

المثال التالي يوضح كيفية التصدير إلى تنسيق ملف APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // تصدير إلى رسوم متحركة بصيغة APNG مع دورات رسوم متحركة غير محدودة كإعداد افتراضي
    image.Save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الرسوم المتحركة
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

### انظر أيضًا

* class [ApngOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../apngoptions/)
* assembly [Aspose.Imaging](../../../)


