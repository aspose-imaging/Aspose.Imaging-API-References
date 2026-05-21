---
title: "Image.UsePalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية Image. تحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة"
type: docs
weight: 170
url: /ar/net/aspose.imaging/image/usepalette/
---
## Image.UsePalette property

يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة.

```csharp
public virtual bool UsePalette { get; }
```

### Property Value

`true` إذا كانت اللوحة مستخدمة في الصورة؛ وإلا، `false`.

## أمثلة

تحديد ما إذا كانت اللوحة مستخدمة من قبل الصورة.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


