---
title: "EmfStockObject"
second_title: "Aspose.Imaging for Java API 参考"
description: "StockObject 枚举指定了可在图形操作中使用的预定义逻辑图形对象的索引。虽然 stock 对象的具体结构取决于实现，但 stock 对象的属性 **SHOULD** 等同于同类型显式创建对象的属性。"
type: docs
weight: 42
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

StockObject 枚举指定了可在图形操作中使用的预定义逻辑图形对象的索引。stock 对象的具体结构取决于实现；然而，stock 对象的属性 **SHOULD** 等同于同类型显式创建对象的属性。这些属性在可能的情况下已为本枚举中定义的 stock 对象指定。
## 字段

| 字段 | 描述 |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | 一种白色实色画刷，相当于逻辑画刷（LogBrushEx 对象，章节 2.2.12），具有以下属性：BrushStyle：BS\\_SOLID（WMF BrushStyle 枚举，[MS-WMF] 章节 2.1.1.4）Color：0x00FFFFFF（WMF ColorRef 对象，[MS-WMF] 章节 2.2.2.8） |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | 一种浅灰色实色画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_SOLID Color：0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | 一种灰色实色画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_SOLID Color：0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | 一种深灰色实色画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_SOLID Color：0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | 一种黑色实色画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_SOLID Color：0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | 一种空画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_NULL |
| [WHITE_PEN](#WHITE-PEN) | 一种白色实色笔，相当于逻辑笔（LogPen 对象，章节 2.2.19），具有以下属性：PenStyle：PS\\_COSMETIC + PS\\_SOLID（PenStyle 枚举，章节 2.1.25）ColorRef：0x00FFFFFF（WMF ColorRef 对象）。 |
| [BLACK_PEN](#BLACK-PEN) | 一种黑色实色笔，相当于逻辑笔，具有以下属性：PenStyle：PS\\_COSMETIC + PS\\_SOLID ColorRef：0x00000000 |
| [NULL_PEN](#NULL-PEN) | 一种空笔，相当于逻辑笔，具有以下属性：PenStyle：PS\\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | 一种等宽 OEM 字符集字体，相当于逻辑字体（LogFont 对象，章节 2.2.13），具有以下属性：Charset：OEM\\_CHARSET（WMF CharacterSet 枚举，[MS-WMF] 章节 2.1.1.5）PitchAndFamily：FF\\_DONTCARE（WMF FamilyFont 枚举，[MS-WMF] 章节 2.1.1.8）+ FIXED\\_PITCH（WMF PitchFont 枚举，[MS-WMF] 章节 2.1.1.24） |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | 一种等宽字体，相当于逻辑字体，具有以下属性：Charset：ANSI\\_CHARSET PitchAndFamily：FF\\_DONTCARE + FIXED\\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | 一种变宽字体，相当于逻辑字体，具有以下属性：Charset：ANSI\\_CHARSET PitchAndFamily：FF\\_DONTCARE + VARIABLE\\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | 一种在操作系统中保证可用的字体。 |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | 当前输出设备的图形设备驱动程序提供的默认字体。 |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | 当前输出设备定义的默认调色板。 |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | 一种在操作系统中保证可用的等宽字体。 |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | 一种在操作系统中保证可用的等宽字体。 |
| [DC_BRUSH](#DC-BRUSH) | 当前在回放设备上下文中选中的实色画刷 |
| [DC_PEN](#DC-PEN) | 当前在回放设备上下文中选中的实色笔 |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


一种白色实色画刷，相当于逻辑画刷（LogBrushEx 对象，章节 2.2.12），具有以下属性：BrushStyle：BS\\_SOLID（WMF BrushStyle 枚举，[MS-WMF] 章节 2.1.1.4）Color：0x00FFFFFF（WMF ColorRef 对象，[MS-WMF] 章节 2.2.2.8）

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


一种浅灰色实色画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_SOLID Color：0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


一种灰色实色画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_SOLID Color：0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


一种深灰色实色画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_SOLID Color：0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


一种黑色实色画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_SOLID Color：0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


一种空画刷，相当于逻辑画刷，具有以下属性：BrushStyle：BS\\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


一种白色实色笔，相当于逻辑笔（LogPen 对象，章节 2.2.19），具有以下属性：PenStyle：PS\\_COSMETIC + PS\\_SOLID（PenStyle 枚举，章节 2.1.25）ColorRef：0x00FFFFFF（WMF ColorRef 对象）。

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


一种黑色实色笔，相当于逻辑笔，具有以下属性：PenStyle：PS\\_COSMETIC + PS\\_SOLID ColorRef：0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


一种空笔，相当于逻辑笔，具有以下属性：PenStyle：PS\\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


一种等宽 OEM 字符集字体，相当于逻辑字体（LogFont 对象，章节 2.2.13），具有以下属性：Charset：OEM\\_CHARSET（WMF CharacterSet 枚举，[MS-WMF] 章节 2.1.1.5）PitchAndFamily：FF\\_DONTCARE（WMF FamilyFont 枚举，[MS-WMF] 章节 2.1.1.8）+ FIXED\\_PITCH（WMF PitchFont 枚举，[MS-WMF] 章节 2.1.1.24）

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


一种等宽字体，相当于逻辑字体，具有以下属性：Charset：ANSI\\_CHARSET PitchAndFamily：FF\\_DONTCARE + FIXED\\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


一种变宽字体，相当于逻辑字体，具有以下属性：Charset：ANSI\\_CHARSET PitchAndFamily：FF\\_DONTCARE + VARIABLE\\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


一种保证在操作系统中可用的字体。此值指定的实际字体取决于实现。

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


由图形设备驱动程序为当前输出设备提供的默认字体。此值指定的实际字体取决于实现。

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


为当前输出设备定义的默认调色板。此值指定的实际调色板取决于实现。

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


一种保证在操作系统中可用的等宽字体。此值指定的实际字体取决于实现。

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


一种保证在操作系统中可用的等宽字体。此值指定的实际字体取决于实现。

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


当前在回放设备上下文中选中的实色画刷

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


当前在回放设备上下文中选中的实色笔

