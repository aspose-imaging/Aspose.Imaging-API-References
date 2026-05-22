---
title: "DjvuImage.Pages"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 属性。使用此属性访问 DjVu 图像集合中的各个页面。通过直接访问每页，简化对 DjVu 格式文档或书籍的导航和操作。借助轻松的页面检索，提高工作流效率。"
type: docs
weight: 120
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/pages/
---
## DjvuImage.Pages property

使用此属性访问 DjVu 图像集合的各个页面。通过直接访问每页，简化对存储在 DjVu 格式中的文档或书籍的导航和操作。通过轻松的页面检索提升工作流效率。

```csharp
public override Image[] Pages { get; }
```

### Property Value

这些页面。

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

* class [Image](../../../aspose.imaging/image/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


