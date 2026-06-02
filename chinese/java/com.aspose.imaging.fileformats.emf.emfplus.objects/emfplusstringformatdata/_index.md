---
title: "EmfPlusStringFormatData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusStringFormatData 对象指定图形字符串的制表位和字符位置。"
type: docs
weight: 75
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

EmfPlusStringFormatData 对象指定图形字符串的制表位和字符位置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTabStops()](#getTabStops--) | 获取或设置一个可选的浮点数数组，指定此对象的可选制表位位置。 |
| [setTabStops(float[] value)](#setTabStops-float---) | 获取或设置一个可选的浮点数数组，指定此对象的可选制表位位置。 |
| [getCharRange()](#getCharRange--) | 获取或设置一个可选的 RangeCount EmfPlusCharacterRange 对象数组，指定文本字符串中字符位置的范围。 |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | 获取或设置一个可选的 RangeCount EmfPlusCharacterRange 对象数组，指定文本字符串中字符位置的范围。 |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


获取或设置一个可选的浮点数数组，指定此对象的可选制表位位置。每个制表位值表示制表位之间的空格数，或者对于第一个制表位，表示文本行起始位置与第一个制表位之间的空格数。如果 EmfPlusStringFormat 对象中的 TabStopCount 字段值大于 0，则此字段必须存在。

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


获取或设置一个可选的浮点数数组，指定此对象的可选制表位位置。每个制表位值表示制表位之间的空格数，或者对于第一个制表位，表示文本行起始位置与第一个制表位之间的空格数。如果 EmfPlusStringFormat 对象中的 TabStopCount 字段值大于 0，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


获取或设置一个可选的 RangeCount EmfPlusCharacterRange 对象数组，指定文本字符串中字符位置的范围。边界区域由字符范围指定的字符组所占据的显示区域定义。如果 EmfPlusStringFormat 对象中的 RangeCount 字段值大于 0，则此字段必须存在。

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


获取或设置一个可选的 RangeCount EmfPlusCharacterRange 对象数组，指定文本字符串中字符位置的范围。边界区域由字符范围指定的字符组所占据的显示区域定义。如果 EmfPlusStringFormat 对象中的 RangeCount 字段值大于 0，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |

