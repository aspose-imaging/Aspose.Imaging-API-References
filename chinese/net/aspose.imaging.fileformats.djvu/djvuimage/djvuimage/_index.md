---
title: "DjvuImage.DjvuImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 构造函数。通过使用 Stream 参数初始化 DjvuImage 类的新实例，开始使用 DjVu 图像。非常适合希望将 DjVu 图像处理无缝集成到项目中的开发者。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/djvuimage/
---
## DjvuImage(Stream) {#constructor}

通过使用 Stream 参数初始化 [`DjvuImage`](../) 类的新实例，开始使用 DjVu 图像。非常适合希望将 DjVu 图像处理无缝集成到项目中的开发者。

```csharp
public DjvuImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception/) | 流为空 |

## 示例

此示例展示了如何从文件流加载 DJVU 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // 将每个页面保存为单独的 PNG 图像。
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // 根据页码生成文件名。
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## DjvuImage(Stream, LoadOptions) {#constructor_1}

使用此构造函数可无缝开始使用 DjVu 图像，它使用 Stream 和 LoadOptions 参数初始化一个新的 [`DjvuImage`](../) 类实例。非常适合希望在保持简洁高效的同时，对 DjVu 图像加载选项进行精确控制的开发者。

```csharp
public DjvuImage(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要加载的流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception/) | 流为空 |

## 示例

此示例展示了如何从文件流加载 DJVU 图像，以保持在指定的内存限制内。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    // 所有内部缓冲区允许的最大大小为 1MB。
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 1 * 1024 * 1024;

    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream, loadOptions))
    {
        // 将每个页面保存为单独的 PNG 图像。
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // 根据页码生成文件名。
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### 另请参见

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


