---
title: "EmfPlusBrush"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusBrush 对象指定用于填充区域的图形画刷。"
type: docs
weight: 24
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

EmfPlusBrush 对象指定用于填充区域的图形画刷。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrushData()](#getBrushData--) | 获取或设置 Brush 数据的可变长度数据，定义在 Type 字段中指定的画笔对象。 |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | 获取或设置 Brush 数据的可变长度数据，定义在 Type 字段中指定的画笔对象。 |
| [getType()](#getType--) | 获取或设置类型。 |
| [setType(int value)](#setType-int-) | 获取或设置类型。 |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


获取或设置 Brush 数据的可变长度数据，定义在 Type 字段中指定的画笔对象。该数据的内容和格式可能因每种画笔类型而异。EmfPlusHatchBrushData（section 2.2.2.20）（已完成）EmfPlusLinearGradientBrushData 对象（section 2.2.2.24）（已完成）EmfPlusPathGradientBrushData 对象（section 2.2.2.29）（已完成）EmfPlusSolidBrushData 对象（section 2.2.2.43）（已完成）EmfPlusTextureBrushData 对象（section 2.2.2.45）（已完成）

Value: 画笔数据。

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


获取或设置 Brush 数据的可变长度数据，定义在 Type 字段中指定的画笔对象。该数据的内容和格式可能因每种画笔类型而异。EmfPlusHatchBrushData（section 2.2.2.20）（已完成）EmfPlusLinearGradientBrushData 对象（section 2.2.2.24）（已完成）EmfPlusPathGradientBrushData 对象（section 2.2.2.29）（已完成）EmfPlusSolidBrushData 对象（section 2.2.2.43）（已完成）EmfPlusTextureBrushData 对象（section 2.2.2.45）（已完成）

Value: 画笔数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


获取或设置类型。

Value: 一个 32 位无符号整数，指定画笔的类型，该类型决定 BrushData 字段的内容。此值必须在 `EmfPlusBrushType` 枚举中定义。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


获取或设置类型。

Value: 一个 32 位无符号整数，指定画笔的类型，该类型决定 BrushData 字段的内容。此值必须在 `EmfPlusBrushType` 枚举中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

