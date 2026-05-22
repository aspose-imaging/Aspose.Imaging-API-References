---
title: "类 TimeInterval"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.TimeInterval 类。表示以毫秒为单位的时间间隔"
type: docs
weight: 10630
url: /zh/net/aspose.imaging.imageoptions/timeinterval/
---
## TimeInterval class

表示以毫秒为单位的时间间隔

```csharp
public class TimeInterval
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TimeInterval](timeinterval/)(uint, uint) | 初始化 `TimeInterval` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [From](../../aspose.imaging.imageoptions/timeinterval/from/) { get; set; } | 获取或设置起始毫秒数。 |
| [To](../../aspose.imaging.imageoptions/timeinterval/to/) { get; set; } | 获取或设置结束毫秒数。 |

## 示例

基于时间间隔导出 GIF 图像的部分动画。

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

### 另请参见

* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


