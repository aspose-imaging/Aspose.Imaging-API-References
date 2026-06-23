---
title: "EmfScaleWindowExtex"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SCALEWINDOWEXTEX 记录通过使用指定的乘数和除数形成的比例，重新指定回放设备上下文的窗口。"
type: docs
weight: 114
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

EMR\_SCALEWINDOWEXTEX 记录通过使用指定的乘数和除数形成的比例，重新指定回放设备上下文的窗口。

如果设备上下文使用固定比例映射模式，则无法更改范围。只有 MM\_ISOTROPIC 和 MM\_ANISOTROPIC 不是固定比例。窗口范围按如下方式修改：xNewWE = (xOldWE \* xNum) / xDenom，yNewWE = (yOldWE \* yNum) / yDenom。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfScaleWindowExtex` 类的新实例。 |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | 初始化 [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getXNum()](#getXNum--) | 获取或设置一个 32 位有符号整数，指定水平乘数。 |
| [setXNum(int value)](#setXNum-int-) | 获取或设置一个 32 位有符号整数，指定水平乘数。 |
| [getXDenom()](#getXDenom--) | 获取或设置一个 32 位有符号整数，指定水平除数。 |
| [setXDenom(int value)](#setXDenom-int-) | 获取或设置一个 32 位有符号整数，指定水平除数。 |
| [getYNum()](#getYNum--) | 获取或设置一个 32 位有符号整数，指定垂直乘数。 |
| [setYNum(int value)](#setYNum-int-) | 获取或设置一个 32 位有符号整数，指定垂直乘数。 |
| [getYDenom()](#getYDenom--) | 获取或设置一个 32 位有符号整数，指定垂直除数。 |
| [setYDenom(int value)](#setYDenom-int-) | 获取或设置一个 32 位有符号整数，指定垂直除数。 |
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


初始化 `EmfScaleWindowExtex` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


初始化 [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex) 类的新实例。

### getXNum() {#getXNum--}
```
public int getXNum()
```


获取或设置一个 32 位有符号整数，指定水平乘数。必须不为零。

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


获取或设置一个 32 位有符号整数，指定水平乘数。必须不为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


获取或设置一个 32 位有符号整数，指定水平除数。必须不为零。

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


获取或设置一个 32 位有符号整数，指定水平除数。必须不为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


获取或设置一个 32 位有符号整数，指定垂直乘数。必须不为零。

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


获取或设置一个 32 位有符号整数，指定垂直乘数。必须不为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


获取或设置一个 32 位有符号整数，指定垂直除数。必须不为零。

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


获取或设置一个 32 位有符号整数，指定垂直除数。必须不为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

