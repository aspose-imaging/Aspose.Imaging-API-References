---
title: EmfStockObject
second_title: Aspose.Imaging for .NET API 参考
description: StockObject 枚举指定可用于图形操作的预定义逻辑图形对象 的索引stock 对象的具体结构是 实现相关的然而库存对象的属性应该等同于 明确创建的相同类型对象的属性 这些属性是在可能的情况下为该枚举中定义的库存对象指定的
type: docs
weight: 2860
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

StockObject 枚举指定可用于图形操作的预定义逻辑图形对象 的索引。stock 对象的具体结构是 实现相关的；然而，库存对象的属性应该等同于 明确创建的相同类型对象的属性。 这些属性是在可能的情况下为该枚举中定义的库存对象指定的。

```csharp
public enum EmfStockObject
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | 等效于逻辑画笔 （LogBrushEx 对象，第 2.2.12 节）的白色纯色画笔，具有以下属性： BrushStyle：BS_SOLID（WMF BrushStyle 枚举，[MS-WMF] 第 2.1.1.4 节） 颜色：0x00FFFFFF（WMF ColorRef 对象，[MS-WMF] 第 2.2.2.8 节） |
| LTGRAY_BRUSH | `-2147483647` | 一种浅灰色纯色画笔，相当于具有以下属性的逻辑画笔： BrushStyle：BS_SOLID 颜色：0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | 一个灰色的纯色画笔，相当于具有以下属性的逻辑画笔： BrushStyle：BS_SOLID 颜色：0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | 一个深灰色的纯色画笔，相当于具有以下属性的逻辑画笔： BrushStyle：BS_SOLID 颜色：0x00404040 |
| BLACK_BRUSH | `-2147483644` | 黑色纯色画笔，相当于具有以下属性的逻辑画笔： BrushStyle：BS_SOLID 颜色：0x00000000 |
| NULL_BRUSH | `-2147483643` | 相当于具有以下属性的逻辑画笔的空画笔： BrushStyle: BS_NULL |
| WHITE_PEN | `-2147483642` | 等效于逻辑笔的白色纯色笔（LogPen 对象，第 2.2.19 节） 具有以下属性： PenStyle：PS_COSMETIC + PS_SOLID（PenStyle 枚举，第 2.1.25 节） ColorRef：0x00FFFFFF（ WMF ColorRef 对象）. |
| BLACK_PEN | `-2147483641` | 相当于具有以下属性的逻辑笔的黑色纯色笔： PenStyle：PS_COSMETIC + PS_SOLID ColorRef：0x00000000 |
| NULL_PEN | `-2147483640` | 相当于具有以下属性的逻辑笔的空笔： PenStyle：PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | 固定宽度的 OEM 字符集字体，等效于具有以下属性的逻辑字体 （LogFont 对象，第 2.2.13 节）： 字符集：OEM_CHARSET（WMF CharacterSet 枚举，[MS-WMF] 第 2.1.1.5 节) PitchAndFamily：FF_DONTCARE（WMF FamilyFont 枚举，[MS-WMF] 第 2.1.1.8 节） + FIXED_PITCH（WMF PitchFont 枚举，[MS-WMF] 第 2.1.1.24 节） |
| ANSI_FIXED_FONT | `-2147483637` | 等价于具有以下属性的逻辑字体的固定宽度字体： 字符集：ANSI_CHARSET PitchAndFamily：FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | 等效于具有以下属性的逻辑字体的可变宽度字体： 字符集：ANSI_CHARSET PitchAndFamily：FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | 保证在操作系统中可用的字体。 此值指定的实际字体是 implementation-dependent |
| DEVICE_DEFAULT_FONT | `-2147483634` | 图形设备驱动程序为当前输出设备提供的默认字体。 此值指定的实际字体是 implementation-dependent |
| DEFAULT_PALETTE | `-2147483633` | 为当前输出设备定义的默认调色板。 此值指定的实际调色板是 implementation-dependent |
| SYSTEM_FIXED_FONT | `-2147483632` | 保证在操作系统中可用的固定宽度字体。 此值指定的实际字体是 implementation-dependent |
| DEFAULT_GUI_FONT | `-2147483631` | 保证在操作系统中可用的固定宽度字体。 此值指定的实际字体是 implementation-dependent |
| DC_BRUSH | `-2147483630` | 播放设备上下文中当前选择的纯色画笔 |
| DC_PEN | `-2147483629` | 当前在播放设备上下文中选择的纯色笔 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
