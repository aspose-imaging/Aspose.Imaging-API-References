---
title: NumPlays
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置循环动画的次数 0 表示无限循环
type: docs
weight: 30
url: /zh/net/aspose.imaging.imageoptions/apngoptions/numplays/
---
## ApngOptions.NumPlays property

获取或设置循环动画的次数。 0 表示无限循环。

```csharp
public int NumPlays { get; set; }
```

### 适当的价值

循环次数。

### 例子

以下示例说明如何导出为 APNG 文件格式。

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
        // 导出为具有无限动画周期的 APNG 动画作为 default
    image.Save("Animation1.webp.png", new ApngOptions());
        // 设置动画cycles
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 });     // 5 个周期
}
```

### 也可以看看

* class [ApngOptions](../../apngoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../apngoptions)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
