---
title: "EmfPlusPixelFormat"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "PixelFormat 枚举定义了在 EMF 位图中受支持的像素格式。"
type: docs
weight: 43
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

PixelFormat 枚举定义了 EMF+ 位图支持的像素格式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | 未指定格式。 |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | 该格式为单色，并使用颜色调色板查找表。 |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | 该格式为 16 色，并使用颜色调色板查找表。 |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | 该格式为 256 色，并使用颜色调色板查找表。 |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | 该格式为每像素 16 位，灰度。 |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | 该格式为每像素 16 位；红、绿、蓝分量各使用 5 位。 |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | 该格式为每像素 16 位；红色分量使用 5 位，绿色分量使用 6 位，蓝色分量使用 5 位。 |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | 该格式为每像素 16 位；Alpha 分量使用 1 位，红、绿、蓝分量各使用 5 位。 |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | 该格式为每像素 24 位；红、绿、蓝分量各使用 8 位。 |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | 该格式为每像素 32 位；红、绿、蓝分量各使用 8 位。 |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | 该格式为每像素 32 位；Alpha、红、绿、蓝分量各使用 8 位。 |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | 该格式为每像素 32 位；Alpha、红、绿、蓝分量各使用 8 位。 |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | 该格式为每像素 48 位；红、绿、蓝分量各使用 16 位。 |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | 该格式为每像素 64 位；Alpha、红、绿、蓝分量各使用 16 位。 |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | 该格式为每像素 64 位；Alpha、红、绿、蓝分量各使用 16 位。 |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


未指定格式。

--------------------

像素格式由 [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap) 对象指定。它们的编码如下： - 位 0-7：像素格式常量的枚举，从零开始。 - 位 8-15：每像素的总位数。 - 位 16：如果设置，则颜色值索引到调色板。 - 位 17：如果设置，则颜色值采用 GDI 支持的格式。 - 位 18：如果设置，则颜色值具有 Alpha 分量。 - 位 19：如果设置，则颜色值具有预乘 Alpha 分量。 - 位 20：如果设置，则支持扩展颜色，每通道 16 位。 - 位 21-31：保留。

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


该格式为单色，并使用颜色调色板查找表。

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


该格式为 16 色，并使用颜色调色板查找表。

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


该格式为 256 色，并使用颜色调色板查找表。

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


该格式为每像素 16 位，灰度。

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


该格式为每像素 16 位；红、绿、蓝分量各使用 5 位。剩余的位未使用。

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


该格式为每像素 16 位；红色分量使用 5 位，绿色分量使用 6 位，蓝色分量使用 5 位。

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


该格式为每像素 16 位；Alpha 分量使用 1 位，红、绿、蓝分量各使用 5 位。

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


该格式为每像素 24 位；红、绿、蓝分量各使用 8 位。

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


该格式为每像素 32 位；红、绿、蓝分量各使用 8 位。剩余的 8 位未使用。

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


该格式为每像素 32 位；Alpha、红、绿、蓝分量各使用 8 位。

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


该格式为每像素 32 位；Alpha、红、绿、蓝分量各使用 8 位。红、绿、蓝分量根据 Alpha 分量进行预乘。

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


该格式为每像素 48 位；红、绿、蓝分量各使用 16 位。

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


该格式为每像素 64 位；Alpha、红、绿、蓝分量各使用 16 位。

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


该格式为每像素 64 位；Alpha、红、绿、蓝分量各使用 16 位。红、绿、蓝分量根据 Alpha 分量进行预乘。

