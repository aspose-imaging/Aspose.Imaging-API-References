---
title: "EmfStockObject"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление StockObject определяет индексы предопределённых логических графических объектов, которые могут использоваться в графических операциях. Конкретные структуры объектов stock зависят от реализации, однако свойства объектов stock ДОЛЖНЫ быть эквивалентны свойствам явно созданных объектов того же типа."
type: docs
weight: 42
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

Перечисление StockObject определяет индексы предопределённых логических графических объектов, которые могут использоваться в графических операциях. Конкретные структуры объектов stock зависят от реализации; однако свойства объектов stock ДОЛЖНЫ быть эквивалентны свойствам явно созданных объектов того же типа. По возможности эти свойства указаны для объектов stock, определённых в данном перечислении.
## Поля

| Поле | Описание |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | Белая кисть сплошного цвета, эквивалентная логической кисти (объект LogBrushEx, раздел 2.2.12) со следующими свойствами: BrushStyle: BS\_SOLID (перечисление WMF BrushStyle, [MS-WMF] раздел 2.1.1.4) Color: 0x00FFFFFF (объект WMF ColorRef, [MS-WMF] раздел 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | Светло-серая, сплошного цвета кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | Серая, сплошного цвета кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | Темно-серая, сплошного цвета кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | Черная, сплошного цвета кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | Нулевая кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | Белая, сплошного цвета ручка, эквивалентная логической ручке (объект LogPen, раздел 2.2.19) со следующими свойствами: PenStyle: PS\_COSMETIC + PS\_SOLID (перечисление PenStyle, раздел 2.1.25) ColorRef: 0x00FFFFFF (объект WMF ColorRef). |
| [BLACK_PEN](#BLACK-PEN) | Черная, сплошного цвета ручка, эквивалентная логической ручке со следующими свойствами: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | Нулевая ручка, эквивалентная логической ручке со следующими свойствами: PenStyle: PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | Шрифт фиксированной ширины, набор символов OEM, эквивалентный логическому шрифту (объект LogFont, раздел 2.2.13) со следующими свойствами: Charset: OEM\_CHARSET (перечисление WMF CharacterSet, [MS-WMF] раздел 2.1.1.5) PitchAndFamily: FF\_DONTCARE (перечисление WMF FamilyFont, [MS-WMF] раздел 2.1.1.8) + FIXED\_PITCH (перечисление WMF PitchFont, [MS-WMF] раздел 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | Шрифт фиксированной ширины, эквивалентный логическому шрифту со следующими свойствами: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | Шрифт переменной ширины, эквивалентный логическому шрифту со следующими свойствами: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | Шрифт, гарантированно доступный в операционной системе. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | Шрифт по умолчанию, предоставляемый драйвером графического устройства для текущего выходного устройства. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | Палитра по умолчанию, определённая для текущего выходного устройства. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | Шрифт фиксированной ширины, гарантированно доступный в операционной системе. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | Шрифт фиксированной ширины, гарантированно доступный в операционной системе. |
| [DC_BRUSH](#DC-BRUSH) | Кисть сплошного цвета, в данный момент выбранная в контексте устройства воспроизведения |
| [DC_PEN](#DC-PEN) | Ручка сплошного цвета, в данный момент выбранная в контексте устройства воспроизведения |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


Белая кисть сплошного цвета, эквивалентная логической кисти (объект LogBrushEx, раздел 2.2.12) со следующими свойствами: BrushStyle: BS\_SOLID (перечисление WMF BrushStyle, [MS-WMF] раздел 2.1.1.4) Color: 0x00FFFFFF (объект WMF ColorRef, [MS-WMF] раздел 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


Светло-серая, сплошного цвета кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


Серая, сплошного цвета кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


Темно-серая, сплошного цвета кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


Черная, сплошного цвета кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


Нулевая кисть, эквивалентная логической кисти со следующими свойствами: BrushStyle: BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


Белая, сплошного цвета ручка, эквивалентная логической ручке (объект LogPen, раздел 2.2.19) со следующими свойствами: PenStyle: PS\_COSMETIC + PS\_SOLID (перечисление PenStyle, раздел 2.1.25) ColorRef: 0x00FFFFFF (объект WMF ColorRef).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


Черная, сплошного цвета ручка, эквивалентная логической ручке со следующими свойствами: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


Нулевая ручка, эквивалентная логической ручке со следующими свойствами: PenStyle: PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


Шрифт фиксированной ширины, набор символов OEM, эквивалентный логическому шрифту (объект LogFont, раздел 2.2.13) со следующими свойствами: Charset: OEM\_CHARSET (перечисление WMF CharacterSet, [MS-WMF] раздел 2.1.1.5) PitchAndFamily: FF\_DONTCARE (перечисление WMF FamilyFont, [MS-WMF] раздел 2.1.1.8) + FIXED\_PITCH (перечисление WMF PitchFont, [MS-WMF] раздел 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


Шрифт фиксированной ширины, эквивалентный логическому шрифту со следующими свойствами: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


Шрифт переменной ширины, эквивалентный логическому шрифту со следующими свойствами: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


Шрифт, гарантированно доступный в операционной системе. Фактический шрифт, указанный этим значением, зависит от реализации

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


Шрифт по умолчанию, предоставляемый драйвером графического устройства для текущего выходного устройства. Фактический шрифт, указанный этим значением, зависит от реализации

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


Палитра по умолчанию, определённая для текущего выходного устройства. Фактическая палитра, указанная этим значением, зависит от реализации

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


Шрифт фиксированной ширины, гарантированно доступный в операционной системе. Фактический шрифт, указанный этим значением, зависит от реализации

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


Шрифт фиксированной ширины, гарантированно доступный в операционной системе. Фактический шрифт, указанный этим значением, зависит от реализации

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


Кисть сплошного цвета, в данный момент выбранная в контексте устройства воспроизведения

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


Ручка сплошного цвета, в данный момент выбранная в контексте устройства воспроизведения

