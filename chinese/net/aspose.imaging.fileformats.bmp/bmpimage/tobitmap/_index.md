---
title: "BmpImage.ToBitmap"
second_title: "Aspose.Imaging for .NET API 参考"
description: "BmpImage 方法。使用此简易方法轻松将光栅图像转换为位图。非常适合需要在不同图像格式之间无缝切换的开发者。"
type: docs
weight: 150
url: /zh/net/aspose.imaging.fileformats.bmp/bmpimage/tobitmap/
---
## BmpImage.ToBitmap method

使用此简易方法轻松将光栅图像转换为位图。对于需要在不同图像格式之间无缝切换的开发者而言，这非常理想。

```csharp
public override Bitmap ToBitmap()
```

### 返回值

位图

## 示例

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

### 另请参见

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


