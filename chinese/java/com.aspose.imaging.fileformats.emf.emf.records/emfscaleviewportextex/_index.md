---
title: "EmfScaleViewportExtex"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SCALEVIEWPORTEXTEX 记录通过使用指定的乘数和除数形成的比例，重新指定设备上下文的视口。"
type: docs
weight: 113
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleViewportExtex extends EmfStateRecordType
```

EMR\_SCALEVIEWPORTEXTEX 记录通过使用指定的乘数和除数形成的比例，重新指定设备上下文的视口。

如果设备上下文使用固定比例映射模式，则无法更改范围。只有 MM\_ISOTROPIC 和 MM\_ANISOTROPIC 不是固定比例。视口范围按如下方式修改。xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfScaleViewportExtex(EmfRecord source)](#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfScaleViewportExtex` 类的新实例。 |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex--) | 初始化 [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex) 类的新实例。 |
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
### EmfScaleViewportExtex(EmfRecord source) {#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleViewportExtex(EmfRecord source)
```


初始化 `EmfScaleViewportExtex` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex--}
```
public EmfScaleViewportExtex()
```


初始化 [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex) 类的新实例。

### getXNum() {#getXNum--}
```
public int getXNum()
```


获取或设置一个 32 位有符号整数，指定水平乘数。不能为零。

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


获取或设置一个 32 位有符号整数，指定水平乘数。不能为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


获取或设置一个 32 位有符号整数，指定水平除数。不能为零。

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


获取或设置一个 32 位有符号整数，指定水平除数。不能为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


获取或设置一个 32 位有符号整数，指定垂直乘数。不能为零。

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


获取或设置一个 32 位有符号整数，指定垂直乘数。不能为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


获取或设置一个 32 位有符号整数，指定垂直除数。不能为零。

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


获取或设置一个 32 位有符号整数，指定垂直除数。不能为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

