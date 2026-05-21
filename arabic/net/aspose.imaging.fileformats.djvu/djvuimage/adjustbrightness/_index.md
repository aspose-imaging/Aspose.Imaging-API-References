---
title: "DjvuImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. قم بضبط سطوع صورة باستخدام معلمة محددة لتوفير التحكم في مستويات الإضاءة لتحقيق وضوح بصري أمثل. هذه الطريقة تزيد أو تقلل من السطوع الكلي للصورة مما يسمح بتعديلات دقيقة لتحقيق تأثيرات إضاءة مرغوبة. من خلال تعديل السطوع يمكن للمستخدمين تحسين وضوح الصورة وتعزيز إعادة إنتاج التفاصيل لتجربة مشاهدة محسنة."
type: docs
weight: 150
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/adjustbrightness/
---
## DjvuImage.AdjustBrightness method

قم بضبط *السطوع* للصورة باستخدام معلمة محددة، مما يوفر تحكمًا في مستويات الإضاءة لتحقيق وضوح بصري مثالي. تقوم هذه الطريقة بزيادة أو تقليل السطوع الكلي للصورة، مما يسمح بإجراء تعديلات دقيقة لتحقيق تأثيرات الإضاءة المطلوبة. من خلال تعديل السطوع، يمكن للمستخدمين تحسين رؤية الصورة وتعزيز إعادة إنتاج التفاصيل لتحسين تجربة المشاهدة.

```csharp
public override void AdjustBrightness(int brightness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| السطوع | Int32 | قيمة السطوع. |

## أمثلة

المثال التالي يقوم بإجراء تصحيح السطوع لصورة DJVU.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع هي في النطاق [-255, 255].
    djvuImage.AdjustBrightness(50);
    djvuImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


