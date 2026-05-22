---
title: "MultiPageOptions.Pages"
second_title: "Aspose.Imaging for .NET API 参考"
description: "MultiPageOptions 属性。获取或设置页面"
type: docs
weight: 70
url: /zh/net/aspose.imaging.imageoptions/multipageoptions/pages/
---
## MultiPageOptions.Pages property

获取或设置页面。

```csharp
public int[] Pages { get; set; }
```

### Property Value

这些页面。

## 示例

此示例展示了如何将多页 DJVU 图像转换为多帧 TIFF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
        saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Deflate;

        // 请注意，如果图像是彩色的，它将根据下面的选项自动转换为黑白格式：
        saveOptions.BitsPerSample = new ushort[] { 1 };

        saveOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.DjvuMultiPageOptions();

        // 默认情况下，所有页面将存储到输出 TIFF 中，但可以显式指定所需的页面集合。
        // 仅导出第一页和第二页。
        saveOptions.MultiPageOptions.Pages = new int[] { 0, 1 };

        // 设置页面标题。
        saveOptions.MultiPageOptions.PageTitles = new string[] { "The First Page", "The Second Page" };

        // 保存为 TIFF
        djvuImage.Save(dir + "sample.tif", saveOptions);
    }
}
```

### 另请参见

* class [MultiPageOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../multipageoptions/)
* assembly [Aspose.Imaging](../../../)


