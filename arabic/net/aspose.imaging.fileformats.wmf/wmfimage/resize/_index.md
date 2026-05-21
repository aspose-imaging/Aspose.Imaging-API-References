---
title: "WmfImage.Resize"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة WmfImage. تغيير حجم الصورة بنوع التحجيم المحدد مما يسمح بتعديل مرن للأبعاد مع الحفاظ على نسبة العرض إلى الارتفاع أو تطبيق خوارزميات تحجيم محددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تحجيم دقيقة مخصصة وفق متطلبات تطبيقك"
type: docs
weight: 150
url: /ar/net/aspose.imaging.fileformats.wmf/wmfimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

غيّر حجم الصورة بنوع التحجيم المحدد، مما يسمح بتعديل مرن للأبعاد مع الحفاظ على نسبة العرض إلى الارتفاع أو تطبيق خوارزميات تحجيم محددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تحجيم دقيقة مخصصة وفق متطلبات تطبيقك.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| NotImplementedException |  |

## أمثلة

هذا المثال يحمل صورة WMF ويعيد تحجيمها باستخدام طرق تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.BilinearResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

ضبط حجم الصورة بناءً على الإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة العرض إلى الارتفاع وسلوك التحجيم. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تحجيم مخصصة موجهة إلى المتطلبات المحددة لتطبيقك.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| الإعدادات | ImageResizeSettings | إعدادات التحجيم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| NotImplementedException |  |

### انظر أيضًا

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


