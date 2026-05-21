---
title: "TgaImage.TgaImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage constructor. يهيئ كائن TgaImage جديد باستخدام مسار الملف المقدم لتحميل محتوى الصورة. يقوم هذا المنشئ بتهيئة نسخة الصورة بكفاءة مما يسمح بالوصول السلس إلى ملفات صور TGA مبسطًا دمجها في سير عمل تطبيقك."
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/tgaimage/
---
## TgaImage(string) {#constructor_2}

Initializes a new [`TgaImage`](../) object using the provided file path for loading the image content. This constructor efficiently initializes the image instance, allowing seamless access to TGA image files, simplifying integration into your application workflow.

```csharp
public TgaImage(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | The path to load an image. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | Specified path is null. |

### انظر أيضًا

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)

---

## TgaImage(RasterImage) {#constructor}

Create a new instance of the [`TgaImage`](../) class by providing a raster image object. This constructor facilitates the direct integration of existing raster images into the TGA image format, streamlining the conversion process for enhanced compatibility within your software systems.

```csharp
public TgaImage(RasterImage rasterImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |

## أمثلة

Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)

---

## TgaImage(Stream) {#constructor_1}

Initialize a new instance of the [`TgaImage`](../) class using a stream to load the image. This constructor allows for seamless integration of image data from streams, facilitating efficient handling and processing of TGA images within your software applications.

```csharp
public TgaImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | The stream to load an image. |

### انظر أيضًا

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


