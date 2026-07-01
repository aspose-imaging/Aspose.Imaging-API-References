---
title: "Pen"
second_title: "Aspose.Imaging for Java API 参考"
description: "定义用于绘制线条、曲线和图形的对象。"
type: docs
weight: 81
url: /zh/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

定义用于绘制线条、曲线和图形的对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | 使用指定的颜色初始化 `Pen` 类的新实例。 |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | 使用指定的 `Color` 和 `Pen.Width` 属性初始化 `Pen` 类的新实例。 |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | 使用指定的 `Brush` 初始化 `Pen` 类的新实例。 |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | 使用指定的 `Brush` 和 `Pen.Width` 初始化 `Pen` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取此 `Pen` 的宽度，单位为绘图所使用的 Graphics 对象的单位。 |
| [setWidth(float value)](#setWidth-float-) | 设置此 `Pen` 的宽度，单位为绘图所使用的 Graphics 对象的单位。 |
| [getStartCap()](#getStartCap--) | 获取使用此 `Pen` 绘制的线条起始端的帽子样式。 |
| [setStartCap(int value)](#setStartCap-int-) | 设置使用此 `Pen` 绘制的线条起始端的帽子样式。 |
| [getEndCap()](#getEndCap--) | 获取使用此 `Pen` 绘制的线条末端的帽子样式。 |
| [setEndCap(int value)](#setEndCap-int-) | 设置使用此 `Pen` 绘制的线条末端的帽子样式。 |
| [getDashCap()](#getDashCap--) | 获取使用此 `Pen` 绘制的虚线中破折号末端的帽子样式。 |
| [setDashCap(int value)](#setDashCap-int-) | 设置使用此 `Pen` 绘制的虚线中破折号末端的帽子样式。 |
| [getLineJoin()](#getLineJoin--) | 获取使用此 `Pen` 绘制的两条连续线段端点的连接样式。 |
| [setLineJoin(int value)](#setLineJoin-int-) | 设置使用此 `Pen` 绘制的两条连续线段端点的连接样式。 |
| [getCustomStartCap()](#getCustomStartCap--) | 获取使用此 `Pen` 绘制的线段起始处的自定义帽子。 |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | 设置使用此 `Pen` 绘制的线段起始处的自定义帽子。 |
| [getCustomEndCap()](#getCustomEndCap--) | 获取使用此 `Pen` 绘制的线段末端的自定义帽子。 |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | 设置使用此 `Pen` 绘制的线段末端的自定义帽子。 |
| [getMiterLimit()](#getMiterLimit--) | 获取斜接角连接处厚度的上限。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 设置斜接角连接处厚度的上限。 |
| [getAlignment()](#getAlignment--) | 获取此 `Pen` 的对齐方式。 |
| [setAlignment(int value)](#setAlignment-int-) | 设置此 `Pen` 的对齐方式。 |
| [getTransform()](#getTransform--) | 获取此 `Pen` 的几何变换的副本。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | 设置此 `Pen` 的几何变换的副本。 |
| [getPenType()](#getPenType--) | 获取使用此 `Pen` 绘制的线条样式。 |
| [getColor()](#getColor--) | 获取此 `Pen` 的颜色。 |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | 设置此 `Pen` 的颜色。 |
| [getBrush()](#getBrush--) | 获取决定此 `Pen` 属性的 `Brush`。 |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | 设置决定此 `Pen` 属性的 `Brush`。 |
| [getDashStyle()](#getDashStyle--) | 获取使用此 `Pen` 绘制的虚线的样式。 |
| [setDashStyle(int value)](#setDashStyle-int-) | 设置使用此 `Pen` 绘制的虚线的样式。 |
| [getDashOffset()](#getDashOffset--) | 获取从线段起点到破折号模式起始处的距离。 |
| [setDashOffset(float value)](#setDashOffset-float-) | 设置从线段起点到破折号模式起始处的距离。 |
| [getDashPattern()](#getDashPattern--) | 获取自定义破折号和空格的数组。 |
| [setDashPattern(float[] value)](#setDashPattern-float---) | 设置自定义破折号和空格的数组。 |
| [getCompoundArray()](#getCompoundArray--) | 获取指定复合笔的值数组。 |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | 设置一个指定复合笔的值数组。 |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | 设置决定此 `Pen` 绘制的线条结束帽样式的值。 |
| [resetTransform()](#resetTransform--) | 将此 `Pen` 的几何变换矩阵重置为单位矩阵。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | 将此 `Pen` 的变换矩阵乘以指定的 `Matrix`。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | 按照指定顺序将此 `Pen` 的变换矩阵乘以指定的 `Matrix`。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的尺寸平移局部几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按照指定顺序按指定的尺寸平移局部几何变换。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定的因子缩放局部几何变换。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按照指定顺序按指定的因子缩放局部几何变换。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定的角度旋转局部几何变换。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按照指定顺序按指定的角度旋转局部几何变换。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) |  |

## Example: This example shows the creation and usage Pen objects.
此示例展示了 Pen 对象的创建和使用。示例创建一个新的 Image 并在 Image 表面绘制矩形。
``` java

// 创建 BmpOptions 的实例并设置其各项属性
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// 创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
// 第二个 Boolean 参数决定要创建的文件是否为 IsTemporal。
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// 在指定路径创建 Image 实例
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // 创建 Graphics 实例并使用 Image 对象进行初始化
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // 使用白色清除 Graphics 表面
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // 创建一个颜色为红色、宽度为 5 的 Pen 实例
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // 创建 HatchBrush 实例并设置其属性
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // 创建 Pen 实例并使用 HatchBrush 对象和宽度进行初始化
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // 通过指定 Pen 对象绘制矩形
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // 通过指定 Pen 对象绘制矩形
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

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


使用指定的颜色初始化 `Pen` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | 一个指示此 `Pen` 颜色的 `Color` 结构。 |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


使用指定的 `Color` 和 `Pen.Width` 属性初始化 `Pen` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | 一个指示此 `Pen` 颜色的 `Color` 结构。 |
| width | float | 指示此 `Pen` 宽度的值。 |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


使用指定的 `Brush` 初始化 `Pen` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | 决定此 `Pen` 填充属性的 `Brush`。 |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


使用指定的 `Brush` 和 `Pen.Width` 初始化 `Pen` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | 决定此 `Pen` 特性的 `Brush`。 |
| width | float | 新 `Pen` 的宽度。 |

### getWidth() {#getWidth--}
```
public float getWidth()
```


获取此 `Pen` 的宽度，单位为绘图所使用的 Graphics 对象的单位。

**Returns:**
float - 此 `Pen` 的宽度。
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


设置此 `Pen` 的宽度，单位为绘图所使用的 Graphics 对象的单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Pen` 的宽度。 |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


获取使用此 `Pen` 绘制的线条起始端的帽子样式。

**Returns:**
int - `LineCap` 值之一，表示使用此 `Pen` 绘制的线条起始处的帽子样式。
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


设置使用此 `Pen` 绘制的线条起始端的帽子样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | `LineCap` 值之一，表示使用此 `Pen` 绘制的线条起始处的帽子样式。 |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


获取使用此 `Pen` 绘制的线条末端的帽子样式。

**Returns:**
int - `LineCap` 值之一，表示使用此 `Pen` 绘制的线条末端的帽子样式。
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


设置使用此 `Pen` 绘制的线条末端的帽子样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | `LineCap` 值之一，表示使用此 `Pen` 绘制的线条末端的帽子样式。 |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


获取使用此 `Pen` 绘制的虚线中破折号末端的帽子样式。

**Returns:**
int - `DashCap` 值之一，表示使用此 `Pen` 绘制的虚线中组成破折号的起始和结束处的帽子样式。
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


设置使用此 `Pen` 绘制的虚线中破折号末端的帽子样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | `DashCap` 值之一，表示使用此 `Pen` 绘制的虚线中组成破折号的起始和结束处的帽子样式。 |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


获取使用此 `Pen` 绘制的两条连续线段端点的连接样式。

**Returns:**
int - 表示使用此 `Pen` 绘制的两条连续线段端点的连接样式的 `LineJoin`。
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


设置使用此 `Pen` 绘制的两条连续线段端点的连接样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 表示使用此 `Pen` 绘制的两条连续线段端点的连接样式的 `LineJoin`。 |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


获取使用此 `Pen` 绘制的线段起始处的自定义帽子。

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


设置使用此 `Pen` 绘制的线段起始处的自定义帽子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | 表示使用此 `Pen` 绘制的线条起始处的帽子的 `CustomLineCap`。 |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


获取使用此 `Pen` 绘制的线段末端的自定义帽子。

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


设置使用此 `Pen` 绘制的线段末端的自定义帽子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | 表示使用此 `Pen` 绘制的线条末端的帽子的 `CustomLineCap`。 |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


获取斜接角连接处厚度的上限。

**Returns:**
float - 斜接角处连接厚度的限制。
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


设置斜接角连接处厚度的上限。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 斜接角处连接厚度的限制。 |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


获取此 `Pen` 的对齐方式。

**Returns:**
int - 表示此 `Pen` 对齐方式的 `PenAlignment`。
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


设置此 `Pen` 的对齐方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 表示此 `Pen` 对齐方式的 `PenAlignment`。 |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取此 `Pen` 的几何变换的副本。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


设置此 `Pen` 的几何变换的副本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | 表示此 `Pen` 几何变换的 `Matrix` 的副本。 |

### getPenType() {#getPenType--}
```
public int getPenType()
```


获取使用此 `Pen` 绘制的线条样式。

**Returns:**
int - 指定使用此 `Pen` 绘制的线条样式的 `PenType` 枚举。
### getColor() {#getColor--}
```
public Color getColor()
```


获取此 `Pen` 的颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


设置此 `Pen` 的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 表示此 `Pen` 颜色的 `Color` 结构体。 |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


获取决定此 `Pen` 属性的 `Brush`。

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


设置决定此 `Pen` 属性的 `Brush`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | 决定此 `Pen` 属性的 `Brush`。 |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


获取使用此 `Pen` 绘制的虚线的样式。

**Returns:**
int - 表示使用此 `Pen` 绘制的虚线样式的 `DashStyle`。
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


设置使用此 `Pen` 绘制的虚线的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 表示使用此 `Pen` 绘制的虚线样式的 `DashStyle`。 |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


获取从线段起点到破折号模式起始处的距离。

**Returns:**
float - 从线条起点到破折号模式起始处的距离。
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


设置从线段起点到破折号模式起始处的距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 从线条起点到破折号模式起始处的距离。 |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


获取自定义破折号和空格的数组。

**Returns:**
float[] - 指定虚线中交替的破折号和空格长度的实数数组。
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


设置自定义破折号和空格的数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float[] | 指定虚线中交替的破折号和空格长度的实数数组。 |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


获取一个指定复合笔的值数组。复合笔绘制由平行线和间隔组成的复合线。

**Returns:**
float[] - 一个指定复合数组的实数数组。数组中的元素必须按递增顺序，且不小于 0，也不大于 1。
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


设置一个指定复合笔的值数组。复合笔绘制由平行线和间隔组成的复合线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float[] | 一个指定复合数组的实数数组。数组中的元素必须按递增顺序，且不小于 0，也不大于 1。 |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


设置决定此 `Pen` 绘制的线条结束帽样式的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startCap | int | `LineCap`，表示使用此 `Pen` 绘制的线条起始端的帽子样式。 |
| endCap | int | `LineCap`，表示使用此 `Pen` 绘制的线条末端的帽子样式。 |
| dashCap | int | `LineCap`，表示使用此 `Pen` 绘制的虚线起始或结束端的帽子样式。 |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


将此 `Pen` 的几何变换矩阵重置为单位矩阵。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


将此 `Pen` 的变换矩阵乘以指定的 `Matrix`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 用于乘以变换矩阵的 `Matrix` 对象。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


按照指定顺序将此 `Pen` 的变换矩阵乘以指定的 `Matrix`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 用于乘以变换矩阵的 `Matrix`。 |
| order | int | 执行乘法操作的顺序。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


按指定尺寸平移局部几何变换。此方法将在变换之前预先添加平移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


按照指定顺序按指定的尺寸平移局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | int | 应用平移的顺序（预先或后置）。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


按指定因子缩放局部几何变换。此方法将在变换之前预先添加缩放矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的因子。 |
| sy | float | 在 y 轴方向上缩放变换的因子。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按照指定顺序按指定的因子缩放局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的因子。 |
| sy | float | 在 y 轴方向上缩放变换的因子。 |
| order | int | `MatrixOrder`，指定是后置还是预先添加缩放矩阵。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


按指定角度旋转局部几何变换。此方法将在变换之前预先添加旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


按照指定顺序按指定的角度旋转局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |
| order | int | `MatrixOrder`，指定是后置还是预先添加旋转矩阵。 |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 其他对象。 |

**Returns:**
boolean - 相等比较结果。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int
