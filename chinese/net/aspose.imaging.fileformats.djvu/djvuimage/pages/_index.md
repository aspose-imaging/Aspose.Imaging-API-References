---
title: Pages
second_title: Aspose.Imaging for .NET API 参考
description: 获取页面
type: docs
weight: 120
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/pages/
---
## DjvuImage.Pages property

获取页面。

```csharp
public override Image[] Pages { get; }
```

### 适当的价值

页面。

### 例子

此示例说明如何从文件流加载 DJVU 图像。

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
                // 根据页码生成文件名.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### 也可以看看

* class [Image](../../../aspose.imaging/image)
* class [DjvuImage](../../djvuimage)
* 命名空间 [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->