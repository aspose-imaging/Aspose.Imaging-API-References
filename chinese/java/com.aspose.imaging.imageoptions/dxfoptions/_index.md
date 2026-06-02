---
title: "DxfOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Drawing Interchange Format（DXF）矢量图像创建的 API 提供了针对生成精确且灵活的 AutoCAD 绘图文件的定制解决方案。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

Drawing Interchange Format（DXF）矢量图像创建的 API 提供了针对生成精确且灵活的 AutoCAD 绘图文件的定制解决方案。专门针对文本线和贝塞尔曲线的处理而设计，开发者可以高效地操作这些元素，统计贝塞尔点，并将曲线转换为折线，以实现无缝导出，确保 DXF 矢量图像的兼容性和保真度。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | 拷贝构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | 在将贝塞尔曲线转换为折线时生成的点数，最少 4 个。 |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | 在将贝塞尔曲线转换为折线时生成的点数，最少 4 个。 |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | 当 \#textAsLines 设置为 `true` 时有效。 |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | 当 \#textAsLines 设置为 `true` 时有效。 |
| [getTextAsLines()](#getTextAsLines--) | 文本是应导出为由折线组成的轮廓（默认），还是可编辑的 Autocad TEXT 实体。 |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | 文本是应导出为由折线组成的轮廓（默认），还是可编辑的 Autocad TEXT 实体。 |

## Example: This example demonstrates export to Dxf format

``` java

//创建 Image 实例并使用磁盘位置的现有图像文件进行初始化
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


拷贝构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | 复制的源选项 |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


在将贝塞尔曲线转换为折线时生成的点数，最少 4 个。用于当 (/) 和 (/) 同时 /// 设置为 `true` 时。

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


在将贝塞尔曲线转换为折线时生成的点数，最少 4 个。用于当 (/) 和 (/) 同时 /// 设置为 `true` 时。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


当 \#textAsLines 设置为 `true` 时有效。是否将文本轮廓中的贝塞尔曲线转换为多点折线。

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


当 \#textAsLines 设置为 `true` 时有效。是否将文本轮廓中的贝塞尔曲线转换为多点折线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


文本是应导出为由折线组成的轮廓（默认），还是可编辑的 Autocad TEXT 实体。如果设置了此选项

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


文本是应导出为由折线组成的轮廓（默认），还是可编辑的 Autocad TEXT 实体。如果设置了此选项

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

