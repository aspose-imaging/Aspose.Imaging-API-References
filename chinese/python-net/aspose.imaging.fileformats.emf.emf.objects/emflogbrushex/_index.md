---
title: "EmfLogBrushEx 类"
type: docs
weight: 120
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

**Summary:** The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfLogBrushEx()](#EmfLogBrushEx__1) | 初始化 EmfLogBrushEx 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | 获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），用于指定<br/>            颜色。此字段的解释取决于 BrushStyle 的值，如下表所述。 |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | 获取或设置一个 32 位无符号字段，包含画笔的交叉线数据。其<br/>            解释取决于 BrushStyle 的值， |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | 获取或设置一个 32 位无符号整数，指定画笔样式。该值必须<br/>            来自 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）。本结构支持的样式值将在本节后面列出。BS_NULL 样式<br/>            应用于指定没有效果的画笔。 |


### Constructor: EmfLogBrushEx() {#EmfLogBrushEx__1}


```
 EmfLogBrushEx() 
```

初始化 EmfLogBrushEx 类的新实例

