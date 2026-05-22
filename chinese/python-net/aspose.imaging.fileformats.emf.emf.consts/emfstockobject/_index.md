---
title: "EmfStockObject 枚举"
type: docs
weight: 330
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---

StockObject 枚举指定了预定义逻辑图形对象的索引 <br/>            这些对象可用于图形操作。特定的 StockObject 结构取决于实现；然而，StockObject 的属性应等同于 <br/>            同类型显式创建对象的属性。 <br/>            在可能的情况下，这些属性已为本枚举中定义的 StockObject 指定。

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStockObject

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| ANSI_FIXED_FONT | 一种等宽字体，相当于具有以下属性的逻辑字体：<br/>            字符集: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | 一种变宽字体，相当于具有以下属性的逻辑字体：<br/>            字符集: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| BLACK_BRUSH | 一种黑色实心画刷，相当于具有以下属性的逻辑画刷：<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00000000 |
| BLACK_PEN | 一种黑色实心笔，相当于具有以下属性的逻辑笔：<br/>            PenStyle: PS_COSMETIC + PS_SOLID<br/>            ColorRef: 0x00000000 |
| DC_BRUSH | 当前在回放设备上下文中选中的实心颜色画刷 |
| DC_PEN | 当前在回放设备上下文中选中的实心颜色笔 |
| DEFAULT_GUI_FONT | 一种保证在操作系统中可用的等宽字体。<br/>            此值指定的实际字体取决于实现 |
| DEFAULT_PALETTE | 为当前输出设备定义的默认调色板。<br/>            此值指定的实际调色板取决于实现 |
| DEVICE_DEFAULT_FONT | 由图形设备驱动程序为当前输出设备提供的默认字体。<br/>            此值指定的实际字体取决于实现 |
| DKGRAY_BRUSH | 深灰色、实色画刷，相当于具有以下属性的逻辑画刷：<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00404040 |
| GRAY_BRUSH | 灰色、实色画刷，相当于具有以下属性的逻辑画刷：<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00808080 |
| LTGRAY_BRUSH | 浅灰色、实色画刷，相当于具有以下属性的逻辑画刷：<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00C0C0C0 |
| NULL_BRUSH | 空画刷，相当于具有以下属性的逻辑画刷：<br/>            BrushStyle: BS_NULL |
| NULL_PEN | 空笔，相当于具有以下属性的逻辑笔：<br/>            PenStyle: PS_NULL |
| OEM_FIXED_FONT | 固定宽度、OEM 字符集字体，相当于具有以下属性的逻辑字体 <br/>            (LogFont object, section 2.2.13)：<br/>            Charset: OEM_CHARSET (WMF CharacterSet enumeration, [MS-WMF] section 2.1.1.5)<br/>            PitchAndFamily: FF_DONTCARE (WMF FamilyFont enumeration, [MS-WMF] section 2.1.1.8) <br/>            + FIXED_PITCH (WMF PitchFont enumeration, [MS-WMF] section 2.1.1.24) |
| SYSTEM_FIXED_FONT | 一种保证在操作系统中可用的等宽字体。<br/>            此值指定的实际字体取决于实现 |
| SYSTEM_FONT | 保证在操作系统中可用的字体。 <br/>            由此值指定的实际字体取决于实现。 |
| WHITE_BRUSH | 白色、实色画刷，相当于具有以下属性的逻辑画刷 <br/>            (LogBrushEx object, section 2.2.12)：<br/>            BrushStyle: BS_SOLID (WMF BrushStyle enumeration, [MS-WMF] section 2.1.1.4)<br/>            Color: 0x00FFFFFF (WMF ColorRef object, [MS-WMF] section 2.2.2.8) |
| WHITE_PEN | 白色、实色笔，相当于逻辑笔 (LogPen object, section 2.2.19)<br/>            具有以下属性：<br/>            PenStyle: PS_COSMETIC + PS_SOLID (PenStyle enumeration, section 2.1.25)<br/>            ColorRef: 0x00FFFFFF (WMF ColorRef object)。 |
