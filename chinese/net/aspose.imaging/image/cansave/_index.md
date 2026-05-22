---
title: "Image.CanSave"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。确定图像是否可以保存为由传入的保存选项表示的指定文件格式"
type: docs
weight: 200
url: /zh/net/aspose.imaging/image/cansave/
---
## Image.CanSave method

确定图像是否可以保存为传入保存选项所表示的指定文件格式。

```csharp
public bool CanSave(ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 选项 | ImageOptionsBase | 要使用的保存选项。 |

### 返回值

`true` 表示图像可以保存为传入的保存选项所表示的指定文件格式；否则为 `false`。

## 示例

此示例展示了如何确定图像是否可以保存为传入的保存选项所表示的指定文件格式。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
    saveOptions.Quality = 50;

    // 确定图像是否可以保存为 JPEG
    bool canSave = image.CanSave(saveOptions);
}
```

### 另请参见

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


