---
title: ToBitmap
second_title: Aspose.Imaging for .NET API 参考
description: 将光栅图像转换为位图
type: docs
weight: 140
url: /zh/net/aspose.imaging.fileformats.bmp/bmpimage/tobitmap/
---
## BmpImage.ToBitmap method

将光栅图像转换为位图。

```csharp
public override Bitmap ToBitmap()
```

### 返回值

位图

### 例子

以下示例将 BMP 图像转换为 GDI 位图。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
    System.Drawing.Bitmap bitmap = bmpImage.ToBitmap();

    // 处理 GDI 位图。
}
```

### 也可以看看

* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
