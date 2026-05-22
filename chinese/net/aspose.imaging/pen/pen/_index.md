---
title: "Pen.Pen"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Pen 构造函数。使用指定的颜色初始化 Pen 类的新实例。"
type: docs
weight: 10
url: /zh/net/aspose.imaging/pen/pen/
---
## Pen(Color) {#constructor_2}

使用指定的颜色初始化 [`Pen`](../) 类的新实例。

```csharp
public Pen(Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | Color | 一个指示此 [`Pen`](../) 颜色的 [`Color`](../color/) 结构。 |

### 另请参见

* struct [Color](../../color/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Color, float) {#constructor_3}

使用指定的 [`Color`](../color/) 和 [`Width`](../width/) 属性初始化 [`Pen`](../) 类的新实例。

```csharp
public Pen(Color color, float width)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | Color | 一个指示此 [`Pen`](../) 颜色的 [`Color`](../color/) 结构。 |
| width | Single | 一个指示此 [`Pen`](../) 宽度的值。 |

## 示例

此示例展示了 Pen 对象的创建和使用。示例创建了一个新的 Image 并在图像表面绘制矩形。

```csharp
[C#]

//创建 BmpOptions 的实例并设置其各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//第二个 Boolean 参数决定要创建的文件是否为 IsTemporal
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//在指定路径创建 Image 的实例
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //创建 Graphics 的实例并使用 Image 对象进行初始化
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //使用白色清除 Graphics 表面
    graphics.Clear(Aspose.Imaging.Color.White);

    //创建颜色为 Red、宽度为 5 的 Pen 实例
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //创建 HatchBrush 的实例并设置其属性
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //创建 Pen 的实例
    //使用 HatchBrush 对象和宽度进行初始化
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // 保存所有更改。
    image.Save();
}
```

### 另请参见

* struct [Color](../../color/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Brush) {#constructor}

使用指定的 [`Brush`](../brush/) 初始化 [`Pen`](../) 类的新实例。

```csharp
public Pen(Brush brush)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | 一个决定此 [`Pen`](../) 填充属性的 [`Brush`](../brush/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Brush, float) {#constructor_1}

使用指定的 [`Brush`](../brush/) 和 [`Width`](../width/) 初始化 [`Pen`](../) 类的新实例。

```csharp
public Pen(Brush brush, float width)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | 一个决定此 [`Pen`](../) 特性的 [`Brush`](../brush/)。 |
| width | Single | 新 [`Pen`](../) 的宽度。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)


