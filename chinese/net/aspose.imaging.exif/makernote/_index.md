---
title: "类 MakerNote"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Exif.MakerNote 类。表示单个 Maker Note 记录"
type: docs
weight: 1130
url: /zh/net/aspose.imaging.exif/makernote/
---
## MakerNote class

表示单个 Maker Note 记录。

```csharp
public class MakerNote
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Name](../../aspose.imaging.exif/makernote/name/) { get; } | 获取设置名称。 |
| [Value](../../aspose.imaging.exif/makernote/value/) { get; } | 获取设置值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.imaging.exif/makernote/tostring/)() | 将实例转换为字符串。 |

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

* namespace [Aspose.Imaging.Exif](../../aspose.imaging.exif/)
* assembly [Aspose.Imaging](../../)


