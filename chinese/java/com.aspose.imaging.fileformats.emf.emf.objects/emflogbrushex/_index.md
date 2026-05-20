---
title: "EmfLogBrushEx"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 LogBrushEx 对象定义了设备无关画刷的样式、颜色和图案。"
type: docs
weight: 21
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

LogBrushEx 对象定义了设备无关画刷的样式、颜色和图案。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | 获取或设置一个 32 位无符号整数，用于指定画刷样式。 |
| [setBrushStyle(int value)](#setBrushStyle-int-) | 获取或设置一个 32 位无符号整数，用于指定画刷样式。 |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | 获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），用于指定颜色。 |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | 获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），用于指定颜色。 |
| [getBrushHatch()](#getBrushHatch--) | 获取或设置一个 32 位无符号字段，包含画刷的交叉线数据。 |
| [setBrushHatch(int value)](#setBrushHatch-int-) | 获取或设置一个 32 位无符号字段，包含画刷的交叉线数据。 |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


获取或设置一个 32 位无符号整数，用于指定画刷样式。该值必须是 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）中的一个枚举值。此结构支持的样式值将在本节后面列出。应使用 BS\_NULL 样式来指定没有效果的画刷。

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


获取或设置一个 32 位无符号整数，用于指定画刷样式。该值必须是 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）中的一个枚举值。此结构支持的样式值将在本节后面列出。应使用 BS\_NULL 样式来指定没有效果的画刷。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），用于指定颜色。该字段的解释取决于 BrushStyle 的值，如下表所述。

值：32 位 ARGB 颜色

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），用于指定颜色。该字段的解释取决于 BrushStyle 的值，如下表所述。

值：32 位 ARGB 颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


获取或设置一个 32 位无符号字段，包含画刷的交叉线数据。其解释取决于 BrushStyle 的值，

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


获取或设置一个 32 位无符号字段，包含画刷的交叉线数据。其解释取决于 BrushStyle 的值，

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

