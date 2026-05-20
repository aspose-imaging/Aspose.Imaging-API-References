---
title: "WmfLogColorSpaceW"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "LogColorSpaceW 对象指定一个逻辑颜色空间，该空间可以通过名称由 Unicode 16 位字符组成的颜色配置文件来定义。"
type: docs
weight: 45
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

该 LogColorSpaceW 对象指定逻辑颜色空间，该空间可以由名称由 Unicode 16 位字符组成的颜色配置文件定义。

请参阅 `WmfLogColorSpace` 对象（第 2.2.2.11 节），了解有关解释此对象字段值的更多细节。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSignature()](#getSignature--) | 获取或设置一个 32 位无符号整数，用于指定颜色空间对象的 `signature`；它必须设置为值 0x50534F43，即字符串 \"PSOC\" 的 ASCII 编码。 |
| [setSignature(int value)](#setSignature-int-) | 获取或设置一个 32 位无符号整数，用于指定颜色空间对象的 `signature`；它必须设置为值 0x50534F43，即字符串 \"PSOC\" 的 ASCII 编码。 |
| [getVersion()](#getVersion--) | 获取或设置一个 32 位无符号整数，用于定义 `version` 号；它必须为 0x00000400。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置一个 32 位无符号整数，用于定义 `version` 号；它必须为 0x00000400。 |
| [getSize()](#getSize--) | 获取或设置一个 32 位无符号整数，用于定义此对象的 `size`（单位：字节）。 |
| [setSize(int value)](#setSize-int-) | 获取或设置一个 32 位无符号整数，用于定义此对象的 `size`（单位：字节）。 |
| [getColorSpaceType()](#getColorSpaceType--) | 获取或设置一个 32 位有符号整数，用于指定颜色空间类型。 |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | 获取或设置一个 32 位有符号整数，用于指定颜色空间类型。 |
| [getIntent()](#getIntent--) | 获取或设置一个 32 位有符号整数，用于定义色域映射意图。 |
| [setIntent(int value)](#setIntent-int-) | 获取或设置一个 32 位有符号整数，用于定义色域映射意图。 |
| [getEndpoints()](#getEndpoints--) | 获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义与位图关联的逻辑颜色空间的 RGB `endpoints` 所对应的三种颜色的 CIE 色度 x、y、z 坐标。 |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | 获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义与位图关联的逻辑颜色空间的 RGB `endpoints` 所对应的三种颜色的 CIE 色度 x、y、z 坐标。 |
| [getGammaRed()](#getGammaRed--) | 获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。 |
| [setGammaRed(int value)](#setGammaRed-int-) | 获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。 |
| [getGammaGreen()](#getGammaGreen--) | 获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。 |
| [setGammaGreen(int value)](#setGammaGreen-int-) | 获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。 |
| [getGammaBlue()](#getGammaBlue--) | 获取或设置一个 32 位定点值，用于定义蓝色的色调响应曲线。 |
| [setGammaBlue(int value)](#setGammaBlue-int-) | 获取或设置一个 32 位定点值，用于定义蓝色的色调响应曲线。 |
| [getFilename()](#getFilename--) | 获取或设置一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，用于指定包含颜色配置文件的文件名。 |
| [setFilename(String value)](#setFilename-java.lang.String-) | 获取或设置一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，用于指定包含颜色配置文件的文件名。 |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


获取或设置一个 32 位无符号整数，用于指定颜色空间对象的 `signature`；它必须设置为值 0x50534F43，即字符串 \"PSOC\" 的 ASCII 编码。

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


获取或设置一个 32 位无符号整数，用于指定颜色空间对象的 `signature`；它必须设置为值 0x50534F43，即字符串 \"PSOC\" 的 ASCII 编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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
| value | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


获取或设置一个 32 位无符号整数，用于定义此对象的 `size`（单位：字节）。

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


获取或设置一个 32 位无符号整数，用于定义此对象的 `size`（单位：字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


获取或设置一个 32 位有符号整数，用于指定颜色空间类型。它必须在 LogicalColorSpace 枚举（第 2.1.1.14 节）中定义。如果该值为 LCS\\_sRGB 或 LCS\\_WINDOWS\\_COLOR\\_SPACE，则必须使用 sRGB 颜色空间。

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


获取或设置一个 32 位有符号整数，用于指定颜色空间类型。它必须在 LogicalColorSpace 枚举（第 2.1.1.14 节）中定义。如果该值为 LCS\\_sRGB 或 LCS\\_WINDOWS\\_COLOR\\_SPACE，则必须使用 sRGB 颜色空间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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
| value | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义与位图关联的逻辑颜色空间的 RGB `endpoints` 所对应的三种颜色的 CIE 色度 x、y、z 坐标。如果 `ColorSpaceType` 字段未指定 LCS\\_CALIBRATED\\_RGB，则必须忽略此字段。

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义与位图关联的逻辑颜色空间的 RGB `endpoints` 所对应的三种颜色的 CIE 色度 x、y、z 坐标。如果 `ColorSpaceType` 字段未指定 LCS\\_CALIBRATED\\_RGB，则必须忽略此字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\\_CALIBRATED\\_RGB，则必须忽略此字段。

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\\_CALIBRATED\\_RGB，则必须忽略此字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\\_CALIBRATED\\_RGB，则必须忽略此字段。

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\\_CALIBRATED\\_RGB，则必须忽略此字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


获取或设置一个 32 位定点值，用于定义蓝色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\\_CALIBRATED\\_RGB，则必须忽略此字段。

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


获取或设置一个 32 位定点值，用于定义蓝色的色调响应曲线。如果 `ColorSpaceType` 字段未指定 LCS\\_CALIBRATED\\_RGB，则必须忽略此字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


获取或设置一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，用于指定包含颜色配置文件的文件名。如果指定了文件名且 `ColorSpaceType` 字段被设置为 LCS\\_CALIBRATED\\_RGB，则应忽略此结构的其他字段。

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


获取或设置一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，用于指定包含颜色配置文件的文件名。如果指定了文件名且 `ColorSpaceType` 字段被设置为 LCS\\_CALIBRATED\\_RGB，则应忽略此结构的其他字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

