---
title: "EmfLogPenEx"
second_title: "Aspose.Imaging for Java API 参考"
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
| [getPenStyle()](#getPenStyle--) | 获取或设置笔的样式 |
| [setPenStyle(int value)](#setPenStyle-int-) | 获取或设置笔的样式 |
| [getWidth()](#getWidth--) | 获取或设置一个指定笔绘制线条宽度的 32 位无符号整数。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置一个指定笔绘制线条宽度的 32 位无符号整数。 |
| [getBrushStyle()](#getBrushStyle--) | 获取或设置一个指定笔的刷子样式的 32 位无符号整数，来自 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。 |
| [setBrushStyle(int value)](#setBrushStyle-int-) | 获取或设置一个指定笔的刷子样式的 32 位无符号整数，来自 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。 |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。 |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。 |
| [getBrushHatch()](#getBrushHatch--) | 获取或设置刷子的交叉图案。 |
| [setBrushHatch(int value)](#setBrushHatch-int-) | 获取或设置刷子的交叉图案。 |
| [getNumStyleEntities()](#getNumStyleEntities--) | 获取 StyleEntry 字段中指定的数组的元素数量。 |
| [getStyleEntry()](#getStyleEntry--) | 获取或设置一个可选的 32 位无符号整数数组，用于定义此笔绘制的线条中破折号和间隙的长度，当 PenStyle 的值为 PS\_USERSTYLE（笔的线型）时。 |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | 获取或设置一个可选的 32 位无符号整数数组，用于定义此笔绘制的线条中破折号和间隙的长度，当 PenStyle 的值为 PS\_USERSTYLE（笔的线型）时。 |
| [getBrushDibPattern()](#getBrushDibPattern--) | 获取或设置画刷的 dib 图案。 |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置画刷的 dib 图案。 |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


获取或设置笔的样式

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


获取或设置笔的样式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置一个 32 位无符号整数，指定笔绘制的线条宽度。如果 PenStyle 字段中的笔类型是 PS\_GEOMETRIC，则该值以逻辑单位表示宽度；否则，宽度以设备单位表示。如果 PenStyle 字段中的笔类型是 PS\_COSMETIC，则该值必须为 0x00000001。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置一个 32 位无符号整数，指定笔绘制的线条宽度。如果 PenStyle 字段中的笔类型是 PS\_GEOMETRIC，则该值以逻辑单位表示宽度；否则，宽度以设备单位表示。如果 PenStyle 字段中的笔类型是 PS\_COSMETIC，则该值必须为 0x00000001。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


获取或设置一个 32 位无符号整数，指定笔的画刷样式，取自 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。如果 PenStyle 字段中的笔类型是 PS\_GEOMETRIC，则该值必须是 BS\_SOLID 或 BS\_HATCHED。此字段的值可以是 BS\_NULL，但仅当 PenStyle 中指定的线型为 PS\_NULL 时。应使用 BS\_NULL 样式来指定没有效果的画刷。

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


获取或设置一个 32 位无符号整数，指定笔的画刷样式，取自 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。如果 PenStyle 字段中的笔类型是 PS\_GEOMETRIC，则该值必须是 BS\_SOLID 或 BS\_HATCHED。此字段的值可以是 BS\_NULL，但仅当 PenStyle 中指定的线型为 PS\_NULL 时。应使用 BS\_NULL 样式来指定没有效果的画刷。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。此字段的解释取决于 BrushStyle 的值，如本节后面的表所示。

Value: 32 位 ARGB 颜色

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。此字段的解释取决于 BrushStyle 的值，如本节后面的表所示。

Value: 32 位 ARGB 颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


获取或设置画刷的交叉图案。此字段的定义取决于 BrushStyle 的值，如本节后面的表所示。

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


获取或设置画刷的交叉图案。此字段的定义取决于 BrushStyle 的值，如本节后面的表所示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


获取 StyleEntry 字段中指定的数组的元素数量。如果 PenStyle 未指定 PS\_USERSTYLE，则此值应为零。

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


获取或设置一个可选的 32 位无符号整数数组，用于定义此笔绘制的线条中破折号和间隙的长度，当 PenStyle 的值为 PS\_USERSTYLE（笔的线型）时。数组包含由 NumStyleEntries 指定的条目数量，但使用时视为无限重复。数组的第一条目指定第一个破折号的长度。第二条目指定第一个间隙的长度。此后，破折号和间隙的长度交替出现。如果 PenStyle 字段中的笔类型是 PS\_GEOMETRIC，则长度以逻辑单位表示；否则，以设备单位表示。

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


获取或设置一个可选的 32 位无符号整数数组，用于定义此笔绘制的线条中破折号和间隙的长度，当 PenStyle 的值为 PS\_USERSTYLE（笔的线型）时。数组包含由 NumStyleEntries 指定的条目数量，但使用时视为无限重复。数组的第一条目指定第一个破折号的长度。第二条目指定第一个间隙的长度。此后，破折号和间隙的长度交替出现。如果 PenStyle 字段中的笔类型是 PS\_GEOMETRIC，则长度以逻辑单位表示；否则，以设备单位表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


获取或设置画刷的 dib 图案。

值：画刷的 dib 图案。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


获取或设置画刷的 dib 图案。

值：画刷的 dib 图案。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

