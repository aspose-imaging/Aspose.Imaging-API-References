---
title: "EmfPlusFillClosedCurve"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusFillClosedCurve 记录指定填充闭合基数样条的内部。"
type: docs
weight: 32
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

EmfPlusFillClosedCurve 记录指定填充闭合基数样条的内部。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusFillClosedCurve` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isColor()](#isColor--) | 获取或设置一个值，指示此实例是否为颜色。 |
| [setColor(boolean value)](#setColor-boolean-) | 获取或设置一个值，指示此实例是否为颜色。 |
| [getCompressed()](#getCompressed--) | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否已压缩。 |
| [getWinding()](#getWinding--) | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为环绕（winding）模式。 |
| [setWinding(boolean value)](#setWinding-boolean-) | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为环绕（winding）模式。 |
| [getRelative()](#getRelative--) | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为相对的。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为相对的。 |
| [getBrushId()](#getBrushId--) | 获取或设置画刷标识符——一个 32 位无符号整数，指定 EmfPlusBrush，其内容由 Flags 字段中的 S 位决定。 |
| [setBrushId(int value)](#setBrushId-int-) | 获取或设置画刷标识符——一个 32 位无符号整数，指定 EmfPlusBrush，其内容由 Flags 字段中的 S 位决定。 |
| [getTension()](#getTension--) | 获取或设置张力——一个 32 位浮点值，指定样条在通过各点时的弯曲程度。 |
| [setTension(float value)](#setTension-float-) | 获取或设置张力——一个 32 位浮点值，指定样条在通过各点时的弯曲程度。 |
| [getPointData()](#getPointData--) | 获取或设置点数据——一个 Count 点的数组，指定定义样条的线段的端点。 |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | 获取或设置点数据——一个 Count 点的数组，指定定义样条的线段的端点。 |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


初始化 `EmfPlusFillClosedCurve` 类的新实例。

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

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。---------------------- \"winding\" 填充操作按照 \"even-odd parity\" 规则填充区域。根据该规则，可通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点向远离曲线的点画一条直线。如果该直线与曲线相交的次数为奇数，则测试点在曲线内部；否则在曲线外部。--------------------- \"alternate\" 填充操作按照 \"non-zero\" 规则填充区域。根据该规则，可通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点向远离曲线的点画一条直线。统计曲线从左向右穿过测试线的次数，以及从右向左穿过的次数。如果这两个数字相同，测试点在曲线外部；否则在曲线内部。

值：`true` 表示已压缩；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。---------------------- \"winding\" 填充操作按照 \"even-odd parity\" 规则填充区域。根据该规则，可通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点向远离曲线的点画一条直线。如果该直线与曲线相交的次数为奇数，则测试点在曲线内部；否则在曲线外部。--------------------- \"alternate\" 填充操作按照 \"non-zero\" 规则填充区域。根据该规则，可通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点向远离曲线的点画一条直线。统计曲线从左向右穿过测试线的次数，以及从右向左穿过的次数。如果这两个数字相同，测试点在曲线外部；否则在曲线内部。

值：`true` 表示已压缩；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为 winding（环绕）模式。此位指示填充操作的方式。如果设置，填充为 \"winding\" 填充；如果未设置，填充为 \"alternate\" 填充。

值：如果为 winding 则为 `true`；否则为 `false`。

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为 winding（环绕）模式。此位指示填充操作的方式。如果设置，填充为 \"winding\" 填充；如果未设置，填充为 \"alternate\" 填充。

值：如果为 winding 则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为相对的。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置坐标为 (0,0)。如果未设置，则 PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，上面的 C 标志未定义，必须被忽略。

值：`true` 表示相对；否则为 `false`。

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为相对的。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置坐标为 (0,0)。如果未设置，则 PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，上面的 C 标志未定义，必须被忽略。

值：`true` 表示相对；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


获取或设置画笔标识符，一个 32 位无符号整数，指定 EmfPlusBrush，其内容由 Flags 字段中的 S 位决定。此画笔用于填充闭合基数样条的内部。

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


获取或设置画笔标识符，一个 32 位无符号整数，指定 EmfPlusBrush，其内容由 Flags 字段中的 S 位决定。此画笔用于填充闭合基数样条的内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


获取或设置张力，一个 32 位浮点值，指定样条在经过各点时的弯曲程度。值为 0.0 表示样条是一系列直线。值越大，曲线越圆滑。欲了解更多信息，请参阅 [SPLINE77] 和 [PETZOLD]。

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


获取或设置张力，一个 32 位浮点值，指定样条在经过各点时的弯曲程度。值为 0.0 表示样条是一系列直线。值越大，曲线越圆滑。欲了解更多信息，请参阅 [SPLINE77] 和 [PETZOLD]。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


获取或设置点数据，一个由 Count 个点组成的数组，指定定义样条的线段的端点。在闭合基数样条中，曲线会通过 PointData 数组的最后一个点并连接到数组的第一个点。

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


获取或设置点数据，一个由 Count 个点组成的数组，指定定义样条的线段的端点。在闭合基数样条中，曲线会通过 PointData 数组的最后一个点并连接到数组的第一个点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

