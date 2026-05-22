---
title: "EmfPlusStringFormatData 类"
type: docs
weight: 660
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---

**Summary:** The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData__1) | 初始化 EmfPlusStringFormatData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| char_range | [EmfPlusCharacterRange[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange/) | r/w | 获取或设置一个可选的 RangeCount EmfPlusCharacterRange <br/>            对象数组，指定文本字符串中字符位置的范围。<br/>            边界区域由显示区域中被该字符范围指定的一组字符占据的面积定义。<br/>            如果 EmfPlusStringFormat 对象的 RangeCount 字段的值大于 0，则此字段 必须存在。 |
| 制表位 | float[] | r/w | 获取或设置一个可选的浮点值数组，指定 <br/>            此对象的可选制表位位置。每个制表位值表示制表位之间的空格数，或者对于第一个制表位，表示文本行起始处与第一个制表位之间的空格数。<br/>            如果 EmfPlusStringFormat 对象的 TabStopCount 字段的值大于 0，则此字段 必须存在。 |


### Constructor: EmfPlusStringFormatData() {#EmfPlusStringFormatData__1}


```
 EmfPlusStringFormatData() 
```

初始化 EmfPlusStringFormatData 类的新实例

