---
title: "EmfLogPen"
second_title: "Aspose.Imaging for Java API 参考"
description: "LogPen 对象定义了逻辑笔的样式、宽度和颜色。"
type: docs
weight: 27
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

LogPen 对象定义了逻辑笔的样式、宽度和颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | 获取或设置一个 32 位无符号整数，指定 PenStyle。 |
| [setPenStyle(int value)](#setPenStyle-int-) | 获取或设置一个 32 位无符号整数，指定 PenStyle。 |
| [getWidth()](#getWidth--) | 获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象通过其 x 字段的值指定笔的宽度。 |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | 获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象通过其 x 字段的值指定笔的宽度。 |
| [getAffectWidth()](#getAffectWidth--) | 获取或设置影响的宽度。 |
| [setAffectWidth(int value)](#setAffectWidth-int-) | 获取或设置影响的宽度。 |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定笔的颜色值。 |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定笔的颜色值。 |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


获取或设置一个 32 位无符号整数，指定 PenStyle。该值必须从 PenStyle 枚举表中定义，详见第 2.1.25 节。

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


获取或设置一个 32 位无符号整数，指定 PenStyle。该值必须从 PenStyle 枚举表中定义，详见第 2.1.25 节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


获取或设置 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象通过其 x 字段的值指定笔的宽度。必须忽略其 y 字段的值。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


获取或设置 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象通过其 x 字段的值指定笔的宽度。必须忽略其 y 字段的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


获取或设置影响的宽度。

Value: 影响的宽度。

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


获取或设置影响的宽度。

Value: 影响的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定笔的颜色值。

Value: 32 位 ARGB 颜色

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定笔的颜色值。

Value: 32 位 ARGB 颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

