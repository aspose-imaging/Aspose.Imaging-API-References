---
title: "EmfPlusFillPolygon"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusFillPolygon 记录指定填充多边形的内部。"
type: docs
weight: 36
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

EmfPlusFillPolygon 记录指定填充多边形的内部。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusFillPolygon` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isColor()](#isColor--) | 获取或设置一个值，指示此实例是否为颜色。 |
| [setColor(boolean value)](#setColor-boolean-) | 获取或设置一个值，指示此实例是否为颜色。 |
| [isCompressed()](#isCompressed--) | 获取或设置一个值，指示此实例是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示此实例是否已压缩。 |
| [isRelative()](#isRelative--) | 获取或设置指示此实例是否为相对的值。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 获取或设置指示此实例是否为相对的值。 |
| [getBrushId()](#getBrushId--) | 获取或设置画笔标识符——一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。 |
| [setBrushId(int value)](#setBrushId-int-) | 获取或设置画笔标识符——一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。 |
| [getPointData()](#getPointData--) | 获取或设置点数据——一个由 Count 点组成的数组，定义多边形的顶点。 |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | 获取或设置点数据——一个由 Count 点组成的数组，定义多边形的顶点。 |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


初始化 `EmfPlusFillPolygon` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### isColor() {#isColor--}
```
public boolean isColor()
```


获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 以 EmfPlusARGB 对象（section 2.2.2.1）指定颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（section 2.2.1.1）的索引。

值：如果此实例为颜色则为 `true`；否则为 `false`。

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 以 EmfPlusARGB 对象（section 2.2.2.1）指定颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（section 2.2.1.1）的索引。

值：如果此实例为颜色则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


获取或设置指示此实例是否被压缩的值。如果设置，则 PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，则 PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。

值：如果此实例已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置指示此实例是否被压缩的值。如果设置，则 PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，则 PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。

值：如果此实例已压缩则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


获取或设置指示此实例是否为相对的值。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果未设置，则 PointData 根据 C 标志指定绝对位置。

值：如果此实例为相对，则为 `true`；否则为 `false`。

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


获取或设置指示此实例是否为相对的值。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果未设置，则 PointData 根据 C 标志指定绝对位置。

值：如果此实例为相对，则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


获取或设置画笔标识符——一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


获取或设置画笔标识符——一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


获取或设置点数据——一个由 Count 点组成的数组，定义多边形的顶点。数组中的前两个点指定多边形的第一条边。每个后续点指定一条新边，其顶点包括该点和前一个点。如果最后一点与第一点不重合，则它们指定多边形的最后一条边。

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


获取或设置点数据——一个由 Count 点组成的数组，定义多边形的顶点。数组中的前两个点指定多边形的第一条边。每个后续点指定一条新边，其顶点包括该点和前一个点。如果最后一点与第一点不重合，则它们指定多边形的最后一条边。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

