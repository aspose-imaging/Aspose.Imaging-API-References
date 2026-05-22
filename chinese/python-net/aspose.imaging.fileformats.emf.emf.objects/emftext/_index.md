---
title: "EmfText 类"
type: docs
weight: 260
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfText()](#EmfText__1) | 初始化一个新的 EmfText 类实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 字符 | int | r/w | 获取或设置一个 32 位无符号整数，指定字符串中的字符数 |
| dx_buffer | int[] | r/w | 获取或设置可选的字符间距缓冲区<br/>            UndefinedSpace2（变量）：可选的未使用字节数。OutputDx 字段不要求<br/>            紧接在此结构的前一部分之后。<br/>            OutputDx（变量）：一个 32 位无符号整数数组，指定相邻字符单元原点之间的输出间距，单位为逻辑单位。该字段的位置由 offDx 的字节值相对于记录起始位置指定。如果已定义间距，则此字段包含与输出字符串中字符数量相同的值。如果 EmrText 对象的 Options 字段包含 ETO_PDY 标志，则此缓冲区包含的值是字符数的两倍，分别为每个字符的水平和垂直偏移，按此顺序。如果指定了 ETO_RTLREADING，字符将从右向左排列，而不是从左向右。没有其他选项会影响此字段的解释。 |
| glyph_index_buffer | int[] | r/w | 获取或设置可选的字形索引缓冲区。<br/>            如果 options 包含 ETO_GLYPH_INDEX 标志，则输出文本字符串中字符的代码实际上是 TrueType 字体中字符字形的索引（2.1.11 ExtTextOutOptions 枚举）。字形索引是特定于字体的，<br/>            因此要在回放时显示正确的字符，使用的字体必须与生成索引时使用的字体完全相同。 |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | 获取或设置一个 32 位无符号整数，指定如何使用 Rectangle 字段中指定的矩形。<br/>            此字段可以是多个 ExtTextOutOptions <br/>            枚举（第 2.1.11 节）值的组合。 |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个可选的 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象在逻辑单位中定义裁剪<br/>            和/或不透明矩形。此矩形应用于包含记录执行的文本<br/>            输出。 |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定用于定位字符串的参考点坐标。参考点由最后一个<br/>            EMR_SETTEXTALIGN 记录（第 2.3.11.25 节）定义。如果未设置此记录，<br/>            默认对齐方式为 TA_LEFT,TA_TOP。 |
| string_buffer | string | r/w | 获取或设置字符字符串缓冲区<br/>            UndefinedSpace1（变量）：可选的未使用字节数。<br/>            OutputString 字段不要求紧接在此结构的前一部分之后。<br/>            OutputString（变量）：一个字符数组，指定要输出的字符串。<br/>            该字段的位置由 offString 的字节值相对于记录起始位置指定。<br/>            字符数量由 Chars 的值指定。 |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

初始化一个新的 EmfText 类实例

