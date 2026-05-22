---
title: "ApngOptions.NumPlays"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ApngOptions 属性。获取或设置动画循环的次数。0 表示无限循环"
type: docs
weight: 30
url: /zh/net/aspose.imaging.imageoptions/apngoptions/numplays/
---
## ApngOptions.NumPlays property

获取或设置动画循环的次数。0 表示无限循环。

```csharp
public int NumPlays { get; set; }
```

### Property Value

循环的次数。

## 示例

以下示例展示了如何导出为 APNG 文件格式。

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // 导出为 APNG 动画，默认无限循环播放
    image.Save("Animation1.webp.png", new ApngOptions());
    // 设置动画循环次数
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

### 另请参见

* class [ApngOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../apngoptions/)
* assembly [Aspose.Imaging](../../../)


