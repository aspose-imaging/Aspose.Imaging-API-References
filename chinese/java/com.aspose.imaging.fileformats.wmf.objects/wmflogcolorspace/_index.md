---
title: "WmfLogColorSpace"
second_title: "Aspose.Imaging for Java API 参考"
description: "LogColorSpace 对象为回放设备上下文指定逻辑色彩空间，该空间可以是以 ASCII 字符表示的色彩配置文件名称。"
type: docs
weight: 44
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpace extends MetaObject
```

该 LogColorSpace 对象为回放设备上下文指定逻辑颜色空间，可为 ASCII 字符的颜色配置文件名称。

Endpoints、GammaRed、GammaGreen 和 GammaBlue 字段用于指定逻辑色彩空间。Endpoints 字段是一个 CIEXYZTriple 对象，包含色彩空间 RGB 端点的 x、y、z 值。三刺激值 X、Y、Z 与色度值 x、y、z 之间的关系表达如下：x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z)。GammaRed、GammaGreen 和 GammaBlue 字段的值采用 "8.8 fixed point" 格式，这是一种表示非整数数字的技术。每个值由一个零扩展的 8 位整数部分后跟 8 位小数部分组成，合计 16 位左移 8 位。因此，在 32 位中，实际值 N.F 为 00000000nnnnnnnnffffffff00000000，其中 "nnnnnnnn" 和 "ffffffff" 分别是 N 和 F 的二进制表示。例如，对于实数 10.5，nnnnnnnn 为 00001010（二进制 10），ffffffff 为 00000101（二进制 5），完整的 32 位二进制值为 00000000000010100000010100000000，对应十六进制值 0x0A50。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfLogColorSpace()](#WmfLogColorSpace--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSignature()](#getSignature--) | 获取或设置一个 32 位无符号整数，用于指定色彩空间对象的 `signature`；它必须设置为值 0x50534F43，即字符串 "PSOC" 的 ASCII 编码。 |
| [setSignature(int value)](#setSignature-int-) | 获取或设置一个 32 位无符号整数，用于指定色彩空间对象的 `signature`；它必须设置为值 0x50534F43，即字符串 "PSOC" 的 ASCII 编码。 |
| [getVersion()](#getVersion--) | 获取或设置一个 32 位无符号整数，用于定义 `version` 号；它必须为 0x00000400。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置一个 32 位无符号整数，用于定义 `version` 号；它必须为 0x00000400。 |
| [getSize()](#getSize--) | 获取或设置一个 32 位无符号整数，用于定义此对象的 `size`（字节）。 |
| [setSize(int value)](#setSize-int-) | 获取或设置一个 32 位无符号整数，用于定义此对象的 `size`（字节）。 |
| [getColorSpaceType()](#getColorSpaceType--) | 获取或设置一个 32 位有符号整数，用于指定色彩空间类型。 |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | 获取或设置一个 32 位有符号整数，用于指定色彩空间类型。 |
| [getIntent()](#getIntent--) | 获取或设置一个 32 位有符号整数，用于定义色域映射意图。 |
| [setIntent(int value)](#setIntent-int-) | 获取或设置一个 32 位有符号整数，用于定义色域映射意图。 |
| [getEndpoints()](#getEndpoints--) | 获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义与位图关联的逻辑色彩空间的 RGB `endpoints` 所对应的三种颜色的 CIE 色度 x、y、z 坐标。 |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | 获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义与位图关联的逻辑色彩空间的 RGB `endpoints` 所对应的三种颜色的 CIE 色度 x、y、z 坐标。 |
| [getGammaRed()](#getGammaRed--) | 获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。 |
| [setGammaRed(int value)](#setGammaRed-int-) | 获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。 |
| [getGammaGreen()](#getGammaGreen--) | 获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。 |
| [setGammaGreen(int value)](#setGammaGreen-int-) | 获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。 |
| [getGammaBlue()](#getGammaBlue--) | 获取或设置一个 32 位定点值，用于定义蓝色的色调响应曲线。 |
| [setGammaBlue(int value)](#setGammaBlue-int-) | 获取或设置一个 32 位定点值，用于定义蓝色的色调响应曲线。 |
| [getFilename()](#getFilename--) | 获取或设置一个可选的 ASCII 字符串，指定包含色彩配置文件的文件名。 |
| [setFilename(String value)](#setFilename-java.lang.String-) | 获取或设置一个可选的 ASCII 字符串，指定包含色彩配置文件的文件名。 |
### WmfLogColorSpace() {#WmfLogColorSpace--}
```
public WmfLogColorSpace()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


获取或设置一个 32 位无符号整数，用于指定色彩空间对象的 `signature`；它必须设置为值 0x50534F43，即字符串 "PSOC" 的 ASCII 编码。

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


获取或设置一个 32 位无符号整数，用于指定色彩空间对象的 `signature`；它必须设置为值 0x50534F43，即字符串 "PSOC" 的 ASCII 编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


获取或设置一个 32 位无符号整数，用于定义 `version` 号；它必须为 0x00000400。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


获取或设置一个 32 位无符号整数，用于定义 `version` 号；它必须为 0x00000400。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


获取或设置一个 32 位无符号整数，用于定义此对象的 `size`（字节）。

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


获取或设置一个 32 位无符号整数，用于定义此对象的 `size`（字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


获取或设置一个 32 位有符号整数，用于指定色彩空间类型。它必须在 LogicalColorSpace 枚举（第 2.1.1.14 节）中定义。如果该值为 LCS\_sRGB 或 LCS\_WINDOWS\_COLOR\_SPACE，则必须使用 sRGB 色彩空间。

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


获取或设置一个 32 位有符号整数，用于指定色彩空间类型。它必须在 LogicalColorSpace 枚举（第 2.1.1.14 节）中定义。如果该值为 LCS\_sRGB 或 LCS\_WINDOWS\_COLOR\_SPACE，则必须使用 sRGB 色彩空间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


获取或设置一个 32 位有符号整数，用于定义色域映射意图。它必须在 GamutMappingIntent 枚举（第 2.1.1.11 节）中定义。

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


获取或设置一个 32 位有符号整数，用于定义色域映射意图。它必须在 GamutMappingIntent 枚举（第 2.1.1.11 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义与位图关联的逻辑色彩空间的 RGB `endpoints` 所对应的三种颜色的 CIE 色度 x、y、z 坐标。如果 `ColorSpaceType` 字段未指定 LCS\_CALIBRATED\_RGB，则必须忽略此字段。

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义与位图关联的逻辑色彩空间的 RGB `endpoints` 所对应的三种颜色的 CIE 色度 x、y、z 坐标。如果 `ColorSpaceType` 字段未指定 LCS\_CALIBRATED\_RGB，则必须忽略此字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\_CALIBRATED\_RGB，则必须忽略此字段。

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\_CALIBRATED\_RGB，则必须忽略此字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\_CALIBRATED\_RGB，则必须忽略此字段。

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\_CALIBRATED\_RGB，则必须忽略此字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


获取或设置一个 32 位定点值，用于定义蓝色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\_CALIBRATED\_RGB，则必须忽略此字段。

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


获取或设置一个 32 位定点值，用于定义蓝色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\_CALIBRATED\_RGB，则必须忽略此字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


获取或设置一个可选的 ASCII 字符串，指定包含色彩配置文件的文件名。如果指定了文件名，并且 `ColorSpaceType` 字段被设置为 LCS\_CALIBRATED\_RGB，则此结构的其他字段应被忽略。

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


获取或设置一个可选的 ASCII 字符串，指定包含色彩配置文件的文件名。如果指定了文件名，并且 `ColorSpaceType` 字段被设置为 LCS\_CALIBRATED\_RGB，则此结构的其他字段应被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

