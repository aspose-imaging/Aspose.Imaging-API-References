---
title: "ExifData.MakerNotes"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ExifData property. 获取制造商备注"
type: docs
weight: 820
url: /zh/net/aspose.imaging.exif/exifdata/makernotes/
---
## ExifData.MakerNotes property

获取 maker note。

```csharp
public MakerNote[] MakerNotes { get; }
```

### Property Value

制造商备注。

## 示例

在 JPEG 图像中访问相机制造商的 Maker Note。

```csharp
[C#]

using (var image = (JpegImage)Image.Load("Sample.jpg"))
{
    foreach (var makerNote in image.ExifData.MakerNotes)
    {
        Console.WriteLine("Name = {0}, Value = {1}", makerNote.Name, makerNote.Value);
    }
}
```

### 另请参见

* class [MakerNote](../../makernote/)
* class [ExifData](../)
* namespace [Aspose.Imaging.Exif](../../exifdata/)
* assembly [Aspose.Imaging](../../../)


