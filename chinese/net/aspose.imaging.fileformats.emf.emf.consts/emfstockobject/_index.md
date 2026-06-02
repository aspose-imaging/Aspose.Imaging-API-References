---
title: "枚举 EmfStockObject"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfStockObject 枚举。StockObject 枚举指定可在图形操作中使用的预定义逻辑图形对象的索引。虽然 stock 对象的具体结构取决于实现，但 stock 对象的属性应等同于同类型显式创建对象的属性。对于此枚举中定义的 stock 对象，尽可能指定了这些属性。"
type: docs
weight: 2950
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

StockObject 枚举指定了可在图形操作中使用的预定义逻辑图形对象的索引。StockObject 的具体结构取决于实现；然而，StockObject 的属性应等同于同类型显式创建对象的属性。对于此枚举中定义的 StockObject，尽可能指定了这些属性。

```csharp
public enum EmfStockObject
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | 一种白色实色画刷，等同于具有以下属性的逻辑画刷（LogBrushEx 对象，第 2.2.12 节）：BrushStyle：BS_SOLID（WMF BrushStyle 枚举，[MS-WMF] 第 2.1.1.4 节）Color：0x00FFFFFF（WMF ColorRef 对象，[MS-WMF] 第 2.2.2.8 节） |
| LTGRAY_BRUSH | `-2147483647` | 一种浅灰色实色画刷，等同于具有以下属性的逻辑画刷：BrushStyle：BS_SOLID Color：0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | 一种灰色实色画刷，等同于具有以下属性的逻辑画刷：BrushStyle：BS_SOLID Color：0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | 一种深灰色实色画刷，等同于具有以下属性的逻辑画刷：BrushStyle：BS_SOLID Color：0x00404040 |
| BLACK_BRUSH | `-2147483644` | 一种黑色实色画刷，等同于具有以下属性的逻辑画刷：BrushStyle：BS_SOLID Color：0x00000000 |
| NULL_BRUSH | `-2147483643` | 一种空画刷，等同于具有以下属性的逻辑画刷：BrushStyle：BS_NULL |
| WHITE_PEN | `-2147483642` | 一种白色实色笔，等同于具有以下属性的逻辑笔（LogPen 对象，第 2.2.19 节）：PenStyle：PS_COSMETIC + PS_SOLID（PenStyle 枚举，第 2.1.25 节）ColorRef：0x00FFFFFF（WMF ColorRef 对象）。 |
| BLACK_PEN | `-2147483641` | 一种黑色实色笔，等同于具有以下属性的逻辑笔：PenStyle：PS_COSMETIC + PS_SOLID ColorRef：0x00000000 |
| NULL_PEN | `-2147483640` | 一种空笔，等同于具有以下属性的逻辑笔：PenStyle：PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | 一种等宽 OEM 字符集字体，等同于具有以下属性的逻辑字体（LogFont 对象，第 2.2.13 节）：Charset：OEM_CHARSET（WMF CharacterSet 枚举，[MS-WMF] 第 2.1.1.5 节）PitchAndFamily：FF_DONTCARE（WMF FamilyFont 枚举，[MS-WMF] 第 2.1.1.8 节）+ FIXED_PITCH（WMF PitchFont 枚举，[MS-WMF] 第 2.1.1.24 节） |
| ANSI_FIXED_FONT | `-2147483637` | 一种等宽字体，等同于具有以下属性的逻辑字体：Charset：ANSI_CHARSET PitchAndFamily：FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | 一种可变宽度字体，等同于具有以下属性的逻辑字体：Charset：ANSI_CHARSET PitchAndFamily：FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | 一种保证在操作系统中可用的字体。此值指定的实际字体取决于实现。 |
| DEVICE_DEFAULT_FONT | `-2147483634` | 当前输出设备的图形设备驱动程序提供的默认字体。此值指定的实际字体取决于实现。 |
| DEFAULT_PALETTE | `-2147483633` | 为当前输出设备定义的默认调色板。此值指定的实际调色板取决于实现。 |
| SYSTEM_FIXED_FONT | `-2147483632` | 一种保证在操作系统中可用的等宽字体。此值指定的实际字体取决于实现。 |
| DEFAULT_GUI_FONT | `-2147483631` | 一种保证在操作系统中可用的等宽字体。此值指定的实际字体取决于实现。 |
| DC_BRUSH | `-2147483630` | 当前在回放设备上下文中选中的纯色画刷 |
| DC_PEN | `-2147483629` | 当前在回放设备上下文中选中的纯色笔 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


