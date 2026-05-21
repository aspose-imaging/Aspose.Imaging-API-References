---
title: "فئة TimeInterval"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.ImageOptions.TimeInterval. تمثل الفاصل الزمني بالميليثانية."
type: docs
weight: 10630
url: /ar/net/aspose.imaging.imageoptions/timeinterval/
---
## TimeInterval class

يمثل الفاصل الزمني بالمللي ثانية

```csharp
public class TimeInterval
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TimeInterval](timeinterval/)(uint, uint) | يُهيئ مثيلاً جديداً من الفئة `TimeInterval`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [From](../../aspose.imaging.imageoptions/timeinterval/from/) { get; set; } | يحصل أو يضبط From بالميليثانية. |
| [To](../../aspose.imaging.imageoptions/timeinterval/to/) { get; set; } | يحصل أو يضبط To بالميليثانية. |

## أمثلة

تصدير جزء من الرسوم المتحركة من صورة GIF بناءً على الفاصل الزمني.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

### انظر أيضًا

* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


