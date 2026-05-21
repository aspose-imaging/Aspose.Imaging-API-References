---
title: "HatchBrush"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "定义具有填充样式、前景色和背景色的矩形画刷。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

定义具有填充样式、前景色和背景色的矩形画刷。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | 获取填充线的颜色。 |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | 设置填充线的颜色。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取填充线之间间隔的颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 设置填充线之间间隔的颜色。 |
| [getHatchStyle()](#getHatchStyle--) | 获取此画刷的填充样式。 |
| [setHatchStyle(int value)](#setHatchStyle-int-) | 设置此画笔的交叉线样式。 |

## Example: This example shows the creation and usage Pen objects.
此示例展示了 Pen 对象的创建和使用。示例创建了一个新的 Image 并在 Image 表面绘制 Rectangles。
``` java

// 创建 BmpOptions 的实例并设置其各项属性。
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// 创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source。
// 第二个布尔参数决定要创建的文件是否为 IsTemporal。
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// 在指定路径创建 Image 实例
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // 创建 Graphics 实例并使用 Image 对象进行初始化
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // 使用白色清除 Graphics 表面
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // 创建一个颜色为 Red、宽度为 5 的 Pen 实例
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // 创建 HatchBrush 实例并设置其属性
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // 创建 Pen 实例并使用 HatchBrush 对象和宽度进行初始化
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // 通过指定 Pen 对象绘制 Rectangles
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // 通过指定 Pen 对象绘制 Rectangles
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // 保存所有更改。
    image.save();
} finally {
    image.dispose();
}
```

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


获取填充线的颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


设置填充线的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 交叉线的颜色。 |


**Example: This example shows the creation and usage Pen objects.**
此示例展示了 Pen 对象的创建和使用。示例创建了一个新的 Image 并在 Image 表面绘制 Rectangles。
``` java

// 创建 BmpOptions 的实例并设置其各项属性。
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// 创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source。
// 第二个布尔参数决定要创建的文件是否为 IsTemporal。
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// 在指定路径创建 Image 实例
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // 创建 Graphics 实例并使用 Image 对象进行初始化
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // 使用白色清除 Graphics 表面
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // 创建一个颜色为 Red、宽度为 5 的 Pen 实例
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // 创建 HatchBrush 实例并设置其属性
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // 创建 Pen 实例并使用 HatchBrush 对象和宽度进行初始化
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // 通过指定 Pen 对象绘制 Rectangles
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // 通过指定 Pen 对象绘制 Rectangles
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // 保存所有更改。
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取填充线之间间隔的颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


设置填充线之间间隔的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 交叉线之间空隙的颜色。 |


**Example: This example shows the creation and usage Pen objects.**
此示例展示了 Pen 对象的创建和使用。示例创建了一个新的 Image 并在 Image 表面绘制 Rectangles。
``` java

// 创建 BmpOptions 的实例并设置其各项属性。
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// 创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source。
// 第二个布尔参数决定要创建的文件是否为 IsTemporal。
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// 在指定路径创建 Image 实例
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // 创建 Graphics 实例并使用 Image 对象进行初始化
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // 使用白色清除 Graphics 表面
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // 创建一个颜色为 Red、宽度为 5 的 Pen 实例
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // 创建 HatchBrush 实例并设置其属性
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // 创建 Pen 实例并使用 HatchBrush 对象和宽度进行初始化
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // 通过指定 Pen 对象绘制 Rectangles
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // 通过指定 Pen 对象绘制 Rectangles
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // 保存所有更改。
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


获取此画刷的填充样式。

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


设置此画笔的交叉线样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

