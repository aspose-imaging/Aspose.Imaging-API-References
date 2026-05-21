---
title: "EmfStockObject"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "StockObject 枚举指定可在图形操作中使用的预定义逻辑图形对象的索引。StockObject 的具体结构取决于实现，但其属性应等同于同类型显式创建对象的属性。"
type: docs
weight: 42
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

StockObject 枚举指定可在图形操作中使用的预定义逻辑图形对象的索引。StockObject 的具体结构取决于实现；然而，其属性应等同于同类型显式创建对象的属性。对于本枚举中定义的 StockObject，尽可能指定了这些属性。
## 字段

| 字段 | 描述 |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | 一种白色实色画刷，等同于逻辑画刷（LogBrushEx 对象，章节 2.2.12），具有以下属性：BrushStyle：BS\_SOLID（WMF BrushStyle 枚举，[MS-WMF] 章节 2.1.1.4）Color：0x00FFFFFF（WMF ColorRef 对象，[MS-WMF] 章节 2.2.2.8） |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | 一种浅灰色、实色画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | 一种灰色、实色画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | 一种深灰色、实色画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | 一种黑色、实色画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | 一种空画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_NULL |
| [WHITE_PEN](#WHITE-PEN) | 一种白色、实色钢笔，相当于具有以下属性的逻辑钢笔（LogPen 对象，章节 2.2.19）：PenStyle: PS\\_COSMETIC + PS\\_SOLID（PenStyle 枚举，章节 2.1.25）ColorRef: 0x00FFFFFF（WMF ColorRef 对象）。 |
| [BLACK_PEN](#BLACK-PEN) | 一种黑色、实色钢笔，相当于具有以下属性的逻辑钢笔：PenStyle: PS\\_COSMETIC + PS\\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | 一种空钢笔，相当于具有以下属性的逻辑钢笔：PenStyle: PS\\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | 一种固定宽度、OEM 字符集的字体，相当于具有以下属性的逻辑字体（LogFont 对象，章节 2.2.13）：Charset: OEM\\_CHARSET（WMF CharacterSet 枚举，[MS-WMF] 章节 2.1.1.5）PitchAndFamily: FF\\_DONTCARE（WMF FamilyFont 枚举，[MS-WMF] 章节 2.1.1.8）+ FIXED\\_PITCH（WMF PitchFont 枚举，[MS-WMF] 章节 2.1.1.24） |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | 一种固定宽度字体，相当于具有以下属性的逻辑字体：Charset: ANSI\\_CHARSET PitchAndFamily: FF\\_DONTCARE + FIXED\\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | 一种可变宽度字体，相当于具有以下属性的逻辑字体：Charset: ANSI\\_CHARSET PitchAndFamily: FF\\_DONTCARE + VARIABLE\\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | 一种在操作系统中保证可用的字体。 |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | 当前输出设备的图形设备驱动程序提供的默认字体。 |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | 为当前输出设备定义的默认调色板。 |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | 一种在操作系统中保证可用的固定宽度字体。 |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | 一种在操作系统中保证可用的固定宽度字体。 |
| [DC_BRUSH](#DC-BRUSH) | 当前在回放设备上下文中选中的实色画刷 |
| [DC_PEN](#DC-PEN) | 当前在回放设备上下文中选中的实色钢笔 |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


一种白色实色画刷，等同于逻辑画刷（LogBrushEx 对象，章节 2.2.12），具有以下属性：BrushStyle：BS\_SOLID（WMF BrushStyle 枚举，[MS-WMF] 章节 2.1.1.4）Color：0x00FFFFFF（WMF ColorRef 对象，[MS-WMF] 章节 2.2.2.8）

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


一种浅灰色、实色画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


一种灰色、实色画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


一种深灰色、实色画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


一种黑色、实色画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


一种空画刷，相当于具有以下属性的逻辑画刷：BrushStyle: BS\\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


一种白色、实色钢笔，相当于具有以下属性的逻辑钢笔（LogPen 对象，章节 2.2.19）：PenStyle: PS\\_COSMETIC + PS\\_SOLID（PenStyle 枚举，章节 2.1.25）ColorRef: 0x00FFFFFF（WMF ColorRef 对象）。

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


一种黑色、实色钢笔，相当于具有以下属性的逻辑钢笔：PenStyle: PS\\_COSMETIC + PS\\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


一种空钢笔，相当于具有以下属性的逻辑钢笔：PenStyle: PS\\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


一种固定宽度、OEM 字符集的字体，相当于具有以下属性的逻辑字体（LogFont 对象，章节 2.2.13）：Charset: OEM\\_CHARSET（WMF CharacterSet 枚举，[MS-WMF] 章节 2.1.1.5）PitchAndFamily: FF\\_DONTCARE（WMF FamilyFont 枚举，[MS-WMF] 章节 2.1.1.8）+ FIXED\\_PITCH（WMF PitchFont 枚举，[MS-WMF] 章节 2.1.1.24）

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


一种固定宽度字体，相当于具有以下属性的逻辑字体：Charset: ANSI\\_CHARSET PitchAndFamily: FF\\_DONTCARE + FIXED\\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


一种可变宽度字体，相当于具有以下属性的逻辑字体：Charset: ANSI\\_CHARSET PitchAndFamily: FF\\_DONTCARE + VARIABLE\\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


一种在操作系统中保证可用的字体。此值指定的实际字体取决于实现。

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


当前输出设备的图形设备驱动程序提供的默认字体。此值指定的实际字体取决于实现。

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


为当前输出设备定义的默认调色板。此值指定的实际调色板取决于实现。

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


一种在操作系统中保证可用的固定宽度字体。此值指定的实际字体取决于实现。

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


一种在操作系统中保证可用的固定宽度字体。此值指定的实际字体取决于实现。

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


当前在回放设备上下文中选中的实色画刷

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


当前在回放设备上下文中选中的实色钢笔

