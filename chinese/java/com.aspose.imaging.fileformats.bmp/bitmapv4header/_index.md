---
title: "BitmapV4Header"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "BitmapV4Header 结构体是位图信息头文件。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

BitmapV4Header 结构是位图信息头文件。它是 BITMAPINFOHEADER 结构的扩展版本。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRedMask()](#getRedMask--) | 获取或设置指定每个像素的红色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。 |
| [setRedMask(int value)](#setRedMask-int-) | 获取或设置指定每个像素的红色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。 |
| [getGreenMask()](#getGreenMask--) | 获取或设置指定每个像素的绿色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。 |
| [setGreenMask(int value)](#setGreenMask-int-) | 获取或设置指定每个像素的绿色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。 |
| [getBlueMask()](#getBlueMask--) | 获取或设置指定每个像素的蓝色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。 |
| [setBlueMask(int value)](#setBlueMask-int-) | 获取或设置指定每个像素的蓝色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。 |
| [getAlphaMask()](#getAlphaMask--) | 获取或设置指定每个像素的 alpha 分量的颜色掩码。 |
| [setAlphaMask(int value)](#setAlphaMask-int-) | 获取或设置指定每个像素的 alpha 分量的颜色掩码。 |
| [getCSType()](#getCSType--) | 获取或设置 DIB 的颜色空间。 |
| [setCSType(int value)](#setCSType-int-) | 获取或设置 DIB 的颜色空间。 |
| [getEndpoints()](#getEndpoints--) | 获取或设置 CoordinatesTriple 类。 |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | 获取或设置 CoordinatesTriple 类。 |
| [getGammaRed()](#getGammaRed--) | 获取或设置 gamma 红色。 |
| [setGammaRed(int value)](#setGammaRed-int-) | 获取或设置 gamma 红色。 |
| [getGammaGreen()](#getGammaGreen--) | 获取或设置 gamma 绿色。 |
| [setGammaGreen(int value)](#setGammaGreen-int-) | 获取或设置 gamma 绿色。 |
| [getGammaBlue()](#getGammaBlue--) | 获取或设置 gamma 蓝色。 |
| [setGammaBlue(int value)](#setGammaBlue-int-) | 获取或设置 gamma 蓝色。 |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


获取或设置指定每个像素的红色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


获取或设置指定每个像素的红色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


获取或设置指定每个像素的绿色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


获取或设置指定每个像素的绿色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


获取或设置指定每个像素的蓝色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


获取或设置指定每个像素的蓝色分量的颜色掩码，仅在 bV4Compression 设置为 BI\_BITFIELDS 时有效。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


获取或设置指定每个像素的 alpha 分量的颜色掩码。

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


获取或设置指定每个像素的 alpha 分量的颜色掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


获取或设置 DIB 的颜色空间。

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


获取或设置 DIB 的颜色空间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


获取或设置 CoordinatesTriple 类。

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


获取或设置 CoordinatesTriple 类。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | 端点。 |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


获取或设置 gamma 红色。

**Returns:**
int - gamma 红色。
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


获取或设置 gamma 红色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | gamma 红色。 |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


获取或设置 gamma 绿色。

**Returns:**
int - gamma 绿色。
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


获取或设置 gamma 绿色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | gamma 绿色。 |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


获取或设置 gamma 蓝色。

**Returns:**
int - gamma 蓝色。
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


获取或设置 gamma 蓝色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 伽马蓝。 |

