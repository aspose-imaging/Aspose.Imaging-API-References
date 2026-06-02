---
title: "EmfLogPenEx"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "LogPenEx 对象指定扩展逻辑笔的样式宽度和颜色。"
type: docs
weight: 28
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

LogPenEx 对象指定了扩展逻辑笔的样式、宽度和颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | 获取或设置笔的样式。 |
| [setPenStyle(int value)](#setPenStyle-int-) | 获取或设置笔的样式。 |
| [getWidth()](#getWidth--) | 获取或设置一个 32 位无符号整数，指定笔绘制线条的宽度。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置一个 32 位无符号整数，指定笔绘制线条的宽度。 |
| [getBrushStyle()](#getBrushStyle--) | 获取或设置一个 32 位无符号整数，指定笔的刷子样式，来源于 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。 |
| [setBrushStyle(int value)](#setBrushStyle-int-) | 获取或设置一个 32 位无符号整数，指定笔的刷子样式，来源于 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。 |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。 |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。 |
| [getBrushHatch()](#getBrushHatch--) | 获取或设置刷子的交叉图案。 |
| [setBrushHatch(int value)](#setBrushHatch-int-) | 获取或设置刷子的交叉图案。 |
| [getNumStyleEntities()](#getNumStyleEntities--) | 获取 StyleEntry 字段中指定的数组的元素数量。 |
| [getStyleEntry()](#getStyleEntry--) | 获取或设置一个可选的 32 位无符号整数数组，定义当 PenStyle 为 PS\_USERSTYLE 时此笔绘制线条的虚线和间隔长度。 |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | 获取或设置一个可选的 32 位无符号整数数组，定义当 PenStyle 为 PS\_USERSTYLE 时此笔绘制线条的虚线和间隔长度。 |
| [getBrushDibPattern()](#getBrushDibPattern--) | 获取或设置刷子的 dib 图案。 |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置刷子的 dib 图案。 |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


获取或设置笔的样式。

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


获取或设置笔的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置一个 32 位无符号整数，指定笔绘制线条的宽度。如果 PenStyle 字段中的笔类型为 PS\_GEOMETRIC，则该值为逻辑单位宽度；否则，宽度以设备单位指定。如果 PenStyle 字段中的笔类型为 PS\_COSMETIC，则该值必须为 0x00000001。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置一个 32 位无符号整数，指定笔绘制线条的宽度。如果 PenStyle 字段中的笔类型为 PS\_GEOMETRIC，则该值为逻辑单位宽度；否则，宽度以设备单位指定。如果 PenStyle 字段中的笔类型为 PS\_COSMETIC，则该值必须为 0x00000001。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


获取或设置一个 32 位无符号整数，指定笔的刷子样式，来源于 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。如果 PenStyle 字段中的笔类型为 PS\_GEOMETRIC，则该值必须是 BS\_SOLID 或 BS\_HATCHED。该字段的值可以是 BS\_NULL，但仅当 PenStyle 中指定的线条样式为 PS\_NULL 时。BS\_NULL 样式应当用于指定没有效果的刷子。

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


获取或设置一个 32 位无符号整数，指定笔的刷子样式，来源于 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。如果 PenStyle 字段中的笔类型为 PS\_GEOMETRIC，则该值必须是 BS\_SOLID 或 BS\_HATCHED。该字段的值可以是 BS\_NULL，但仅当 PenStyle 中指定的线条样式为 PS\_NULL 时。BS\_NULL 样式应当用于指定没有效果的刷子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。该字段的解释取决于 BrushStyle 的值，如本节后面的表所示。

值：32 位 ARGB 颜色

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。该字段的解释取决于 BrushStyle 的值，如本节后面的表所示。

值：32 位 ARGB 颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


获取或设置刷子的交叉图案。该字段的定义取决于 BrushStyle 的值，如本节后面的表所示。

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


获取或设置刷子的交叉图案。该字段的定义取决于 BrushStyle 的值，如本节后面的表所示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


获取 StyleEntry 字段中指定的数组的元素数量。如果 PenStyle 未指定 PS\_USERSTYLE，则该值应为零。

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


获取或设置一个可选的 32 位无符号整数数组，定义当 PenStyle 为 PS\_USERSTYLE 时此笔绘制线条的虚线和间隔长度。数组包含由 NumStyleEntries 指定的条目数，但使用时视为无限重复。数组的第一条目指定第一段虚线的长度，第二条目指定第一段间隔的长度，随后虚线和间隔长度交替。如果 PenStyle 字段中的笔类型为 PS\_GEOMETRIC，则长度以逻辑单位指定；否则，以设备单位指定。

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


获取或设置一个可选的 32 位无符号整数数组，定义当 PenStyle 为 PS\_USERSTYLE 时此笔绘制线条的虚线和间隔长度。数组包含由 NumStyleEntries 指定的条目数，但使用时视为无限重复。数组的第一条目指定第一段虚线的长度，第二条目指定第一段间隔的长度，随后虚线和间隔长度交替。如果 PenStyle 字段中的笔类型为 PS\_GEOMETRIC，则长度以逻辑单位指定；否则，以设备单位指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


获取或设置刷子的 dib 图案。

值：刷子 dib 图案。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


获取或设置刷子的 dib 图案。

值：刷子 dib 图案。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

