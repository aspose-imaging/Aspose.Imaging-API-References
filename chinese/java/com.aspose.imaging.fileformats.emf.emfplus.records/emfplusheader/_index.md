---
title: "EmfPlusHeader"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusHeader 记录指定元文件中 EMF 数据的起始位置。"
type: docs
weight: 40
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

EmfPlusHeader 记录指定元文件中 EMF+ 数据的开始。EmfPlusHeader 记录必须嵌入在 EMF EMR\_COMMENT\_EMFPLUS 记录中，该记录必须紧跟在元文件的 EMF 头部之后。EMR\_COMMENT\_EMFPLUS 记录在 [MS-EMF] 第 2.3.3.2 节中指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusHeader` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDualMode()](#getDualMode--) | 获取或设置一个值，指示是否为 [dual mode]。 |
| [setDualMode(boolean value)](#setDualMode-boolean-) | 获取或设置一个值，指示是否为 [dual mode]。 |
| [getVideoDisplay()](#getVideoDisplay--) | 获取或设置一个值，指示是否为视频显示。 |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | 获取或设置一个值，指示是否为视频显示。 |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | 获取或设置 EMF plus 标志。 |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | 获取或设置 EMF plus 标志。 |
| [getLogicalDpiX()](#getLogicalDpiX--) | 获取或设置逻辑 dpi x。 |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | 获取或设置逻辑 dpi x。 |
| [getLogicalDpiY()](#getLogicalDpiY--) | 获取或设置逻辑 dpi y。 |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | 获取或设置逻辑 dpi y。 |
| [getVersion()](#getVersion--) | 获取或设置版本。 |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | 获取或设置版本。 |
| [isValid()](#isValid--) | 获取一个值，指示此实例是否有效。 |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


初始化 `EmfPlusHeader` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


获取或设置一个值，指示是否为 [dual mode]。如果设置，则此标志表示该元文件为 \"dual-mode\"，这意味着它包含两套记录，每套记录完整地指定图形内容。如果清除，则图形内容由 EMF+ 记录指定，且可能还有前置 EmfPlusGetDC 记录的 EMF 记录。如果此标志被设置，仅 EMF 记录就应足以定义图形内容。请注意，无论 \"dual-mode\" 标志是否被设置，某些 EMF 记录始终存在，即 EMF 控制记录以及包含 EMF+ 记录的 EMF 记录。EMF 控制记录在 [MS-EMF] 第 2.3.4 节中指定。

值：如果是 [dual mode] 则为 `true`；否则为 `false`。

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


获取或设置一个值，指示是否为 [dual mode]。如果设置，则此标志表示该元文件为 \"dual-mode\"，这意味着它包含两套记录，每套记录完整地指定图形内容。如果清除，则图形内容由 EMF+ 记录指定，且可能还有前置 EmfPlusGetDC 记录的 EMF 记录。如果此标志被设置，仅 EMF 记录就应足以定义图形内容。请注意，无论 \"dual-mode\" 标志是否被设置，某些 EMF 记录始终存在，即 EMF 控制记录以及包含 EMF+ 记录的 EMF 记录。EMF 控制记录在 [MS-EMF] 第 2.3.4 节中指定。

值：如果是 [dual mode] 则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


获取或设置一个值，指示是否为视频显示。如果设置，则此标志表示该元文件是使用针对视频显示的参考设备上下文记录的。如果清除，则该元文件是使用针对打印机的参考设备上下文记录的。

值：如果是 [video display] 则为 `true`；否则为 `false`。

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


获取或设置一个值，指示是否为视频显示。如果设置，则此标志表示该元文件是使用针对视频显示的参考设备上下文记录的。如果清除，则该元文件是使用针对打印机的参考设备上下文记录的。

值：如果是 [video display] 则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


获取或设置 EMF plus 标志。一个 32 位无符号整数，包含有关此元文件记录方式的信息。如果字段的第 31 位被设置，则此标志表示该元文件是使用针对视频显示的参考设备上下文记录的。如果清除，则该元文件是使用针对打印机的参考设备上下文记录的。

值：EMF plus 标志。

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


获取或设置 EMF plus 标志。一个 32 位无符号整数，包含有关此元文件记录方式的信息。如果字段的第 31 位被设置，则此标志表示该元文件是使用针对视频显示的参考设备上下文记录的。如果清除，则该元文件是使用针对打印机的参考设备上下文记录的。

值：EMF plus 标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


获取或设置逻辑 dpi x。一个 32 位无符号整数，指定记录此元文件时的水平分辨率，单位为每英寸像素数。

值：逻辑 dpi x。

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


获取或设置逻辑 dpi x。一个 32 位无符号整数，指定记录此元文件时的水平分辨率，单位为每英寸像素数。

值：逻辑 dpi x。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


获取或设置逻辑 dpi y。一个 32 位无符号整数，指定记录此元文件时的垂直分辨率，单位为每英寸行数。

值：逻辑 dpi y。

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


获取或设置逻辑 dpi y。一个 32 位无符号整数，指定记录此元文件时的垂直分辨率，单位为每英寸行数。

值：逻辑 dpi y。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


获取或设置版本。一个 EmfPlusGraphicsVersion 对象（第 2.2.2.19 节），指定用于创建此元文件的操作系统图形版本。

值：版本。

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


获取或设置版本。一个 EmfPlusGraphicsVersion 对象（第 2.2.2.19 节），指定用于创建此元文件的操作系统图形版本。

值：版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


获取一个值，指示此实例是否有效。

值：如果此实例有效则为 `true`；否则为 `false`。

**Returns:**
boolean
