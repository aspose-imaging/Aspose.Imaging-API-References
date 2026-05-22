---
title: "EmfLogPenEx 类"
type: docs
weight: 190
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | 初始化 EmfLogPenEx 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。<br/>            该字段的解释取决于 BrushStyle 值，如本节后面的表所示。 |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | 获取或设置画刷 dib 图案。 |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | 获取或设置画刷交叉图案。该字段的定义取决于 <br/>            BrushStyle 值，如本节后面的表所示。 |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | 获取或设置 32 位无符号整数，指定来自<br/>            WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）的笔刷样式。<br/>            如果 PenStyle 字段中的笔类型是 PS_GEOMETRIC，则该值必须是 <br/>            BS_SOLID 或 BS_HATCHED。该字段的值可以是 BS_NULL，但仅当 <br/>            PenStyle 中指定的线型为 PS_NULL 时。应使用 BS_NULL 样式 <br/>            来指定没有效果的画刷。 |
| num_style_entities | int | r | 获取 StyleEntry 字段中指定的数组的元素数量。<br/>            如果 PenStyle 未指定 PS_USERSTYLE，则该值应为零。 |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | 获取或设置笔的样式 |
| style_entry | int[] | r/w | 获取或设置一个可选的 32 位无符号整数数组，定义长度<br/>            短划线和间隙的长度，此笔绘制的线段中，当 PenStyle 的值为<br/>            是 PS_USERSTYLE（笔的线型）时。数组包含的条目数量<br/>            由 NumStyleEntries 指定，但其使用方式相当于无限重复<br/>            数组的第一个条目指定第一个短划线的长度。第二个<br/>            条目指定第一个间隙的长度。此后，短划线和间隙的长度交替出现。<br/>            如果 PenStyle 字段中的笔类型是 PS_GEOMETRIC，则长度以<br/>            逻辑单位指定；否则，以设备单位指定。 |
| width | int | r/w | 获取或设置 32 位无符号整数，指定笔绘制的线宽。<br/>            如果 PenStyle 字段中的笔类型是 PS_GEOMETRIC，则该值的宽度为<br/>            逻辑单位；否则，宽度以设备单位指定。<br/>            如果 PenStyle 字段中的笔类型是 PS_COSMETIC，则该值必须为 0x00000001。 |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

初始化 EmfLogPenEx 类的新实例

