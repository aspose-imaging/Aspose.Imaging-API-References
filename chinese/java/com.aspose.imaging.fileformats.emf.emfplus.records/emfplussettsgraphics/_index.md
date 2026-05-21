---
title: "EmfPlusSetTsGraphics"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 EmfPlusSetTSGraphics 记录指定终端服务器中图形设备上下文的状态。"
type: docs
weight: 67
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

该 EmfPlusSetTSGraphics 记录指定终端服务器中图形设备上下文的状态。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetTsGraphics` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | 获取指示是否为 [basic vga colors] 的值。 |
| [getHavePalette()](#getHavePalette--) | 获取指示是否为 [have palette] 的值。 |
| [getAntiAliasMode()](#getAntiAliasMode--) | 获取或设置一个 8 位无符号整数，指定线条渲染的质量，包括线条抗锯齿的类型。 |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | 获取或设置一个 8 位无符号整数，指定线条渲染的质量，包括线条抗锯齿的类型。 |
| [getTextRenderHint()](#getTextRenderHint--) | 获取或设置一个 8 位无符号整数，指定文本渲染的质量，包括文本抗锯齿的类型。 |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | 获取或设置一个 8 位无符号整数，指定文本渲染的质量，包括文本抗锯齿的类型。 |
| [getCompositingMode()](#getCompositingMode--) | 获取或设置一个 8 位无符号整数，指定源颜色如何与背景颜色组合。 |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | 获取或设置一个 8 位无符号整数，指定源颜色如何与背景颜色组合。 |
| [getCompositingQuality()](#getCompositingQuality--) | 获取或设置一个 8 位无符号整数，指定对线条、曲线以及填充区域边缘进行平滑处理的程度，以使其看起来更连续或更清晰。 |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | 获取或设置一个 8 位无符号整数，指定对线条、曲线以及填充区域边缘进行平滑处理的程度，以使其看起来更连续或更清晰。 |
| [getRenderOriginX()](#getRenderOriginX--) | 获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点水平坐标。 |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | 获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点水平坐标。 |
| [getRenderOriginY()](#getRenderOriginY--) | 获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点垂直坐标。 |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | 获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点垂直坐标。 |
| [getTextContrast()](#getTextContrast--) | 获取或设置一个 16 位无符号整数，指定用于渲染抗锯齿和 ClearType 文本的伽马校正值。 |
| [setTextContrast(short value)](#setTextContrast-short-) | 获取或设置一个 16 位无符号整数，指定用于渲染抗锯齿和 ClearType 文本的伽马校正值。 |
| [getFilterType()](#getFilterType--) | 获取或设置一个 8 位无符号整数，指定如何执行缩放，包括拉伸和收缩。 |
| [setFilterType(byte value)](#setFilterType-byte-) | 获取或设置一个 8 位无符号整数，指定如何执行缩放，包括拉伸和收缩。 |
| [getPixelOffset()](#getPixelOffset--) | 获取或设置一个 8 位无符号整数，指定图像和文本渲染过程的整体质量。 |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | 获取或设置一个 8 位无符号整数，指定图像和文本渲染过程的整体质量。 |
| [getWorldToDevice()](#getWorldToDevice--) | 获取或设置一个 192 位 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定世界空间到设备空间的变换。 |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | 获取或设置一个 192 位 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定世界空间到设备空间的变换。 |
| [getPalette()](#getPalette--) | 获取或设置一个可选的 EmfPlusPalette 对象。 |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | 获取或设置一个可选的 EmfPlusPalette 对象。 |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


初始化 `EmfPlusSetTsGraphics` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


获取一个值，指示是否 [basic vga colors]。如果设置，则调色板仅包含基本 VGA 颜色。

值: `true` 如果 [basic vga colors]；否则，`false`。

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


获取一个值，指示是否 [have palette]。如果设置，则此记录在图形状态数据之后的 Palette 字段中包含一个 EmfPlusPalette 对象（第 2.2.2.28 节）。

值: `true` 如果 [have palette]；否则，`false`。

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


获取或设置一个 8 位无符号整数，指定线条渲染的质量，包括线条抗锯齿的类型。它必须在 SmoothingMode 枚举（第 2.1.1.28 节）中定义。

值: 抗锯齿模式。

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


获取或设置一个 8 位无符号整数，指定线条渲染的质量，包括线条抗锯齿的类型。它必须在 SmoothingMode 枚举（第 2.1.1.28 节）中定义。

值: 抗锯齿模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


获取或设置一个 8 位无符号整数，指定文本渲染的质量，包括文本抗锯齿的类型。它必须在 TextRenderingHint 枚举（第 2.1.1.32 节）中定义。

值: 文本渲染提示。

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


获取或设置一个 8 位无符号整数，指定文本渲染的质量，包括文本抗锯齿的类型。它必须在 TextRenderingHint 枚举（第 2.1.1.32 节）中定义。

值: 文本渲染提示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


获取或设置一个 8 位无符号整数，指定源颜色如何与背景颜色组合。它必须是 CompositingMode 枚举（第 2.1.1.5 节）中的一个值。

值: 合成模式。

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


获取或设置一个 8 位无符号整数，指定源颜色如何与背景颜色组合。它必须是 CompositingMode 枚举（第 2.1.1.5 节）中的一个值。

值: 合成模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


获取或设置一个 8 位无符号整数，指定对线条、曲线以及填充区域边缘进行平滑处理的程度，使其看起来更连续或更清晰。它必须是 CompositingQuality 枚举（第 2.1.1.6 节）中的一个值。

值：合成质量。

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


获取或设置一个 8 位无符号整数，指定对线条、曲线以及填充区域边缘进行平滑处理的程度，使其看起来更连续或更清晰。它必须是 CompositingQuality 枚举（第 2.1.1.6 节）中的一个值。

值：合成质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点水平坐标。

值: 渲染原点 X。

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点水平坐标。

值: 渲染原点 X。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点垂直坐标。

值: 渲染原点 Y。

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点垂直坐标。

值: 渲染原点 Y。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


获取或设置一个 16 位无符号整数，指定用于渲染抗锯齿和 ClearType 文本的伽马校正值。该值必须在 0 到 12（含）之间。

值: 文本对比度。

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


获取或设置一个 16 位无符号整数，指定用于渲染抗锯齿和 ClearType 文本的伽马校正值。该值必须在 0 到 12（含）之间。

值: 文本对比度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


获取或设置一个 8 位无符号整数，指定缩放（包括拉伸和收缩）的执行方式。它必须是 FilterType 枚举（第 2.1.1.11 节）中的一个值。

值: 滤镜类型。

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


获取或设置一个 8 位无符号整数，指定缩放（包括拉伸和收缩）的执行方式。它必须是 FilterType 枚举（第 2.1.1.11 节）中的一个值。

值: 滤镜类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


获取或设置一个 8 位无符号整数，指定图像和文本渲染过程的整体质量。它必须是 PixelOffsetMode 枚举（第 2.1.1.26 节）中的一个值。

值: 像素偏移。

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


获取或设置一个 8 位无符号整数，指定图像和文本渲染过程的整体质量。它必须是 PixelOffsetMode 枚举（第 2.1.1.26 节）中的一个值。

值: 像素偏移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


获取或设置一个 192 位 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定世界空间到设备空间的变换。

值: 世界到设备。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


获取或设置一个 192 位 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定世界空间到设备空间的变换。

值: 世界到设备。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


获取或设置一个可选的 EmfPlusPalette 对象。

值: 调色板。

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


获取或设置一个可选的 EmfPlusPalette 对象。

值: 调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

