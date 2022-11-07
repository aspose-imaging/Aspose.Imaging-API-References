---
title: EmfStockObject
second_title: Aspose.Imaging for Java API Reference
description: The StockObject enumeration specifies the indexes of predefined logical graphics objects that can be used in graphics operations.The specific structures of stock objects are implementation-dependent however the properties of stock objects SHOULD be equivalent to the properties of explicitly created objects of the same type.
type: docs
weight: 42
url: /java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

The StockObject enumeration specifies the indexes of predefined logical graphics objects that can be used in graphics operations.The specific structures of stock objects are implementation-dependent; however, the properties of stock objects SHOULD be equivalent to the properties of explicitly created objects of the same type. These properties are specified where possible for the stock objects defined in this enumeration.
## Fields

| Field | Description |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | A white, solid-color brush that is equivalent to a logical brush (LogBrushEx object, section 2.2.12) with the following properties: BrushStyle: BS\_SOLID (WMF BrushStyle enumeration, [MS-WMF] section 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef object, [MS-WMF] section 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | A light gray, solid-color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | A gray, solid-color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | A dark gray, solid color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | A black, solid color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | A null brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | A white, solid-color pen that is equivalent to a logical pen (LogPen object, section 2.2.19) with the following properties: PenStyle: PS\_COSMETIC + PS\_SOLID (PenStyle enumeration, section 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef object). |
| [BLACK_PEN](#BLACK-PEN) | A black, solid-color pen that is equivalent to a logical pen with the following properties: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | A null pen that is equivalent to a logical pen with the following properties: PenStyle: PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | A fixed-width, OEM character set font that is equivalent to a logical font (LogFont object, section 2.2.13) with the following properties: Charset: OEM\_CHARSET (WMF CharacterSet enumeration, [MS-WMF] section 2.1.1.5) PitchAndFamily: FF\_DONTCARE (WMF FamilyFont enumeration, [MS-WMF] section 2.1.1.8) + FIXED\_PITCH (WMF PitchFont enumeration, [MS-WMF] section 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | A fixed-width font that is equivalent to a logical font with the following properties: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | A variable-width font that is equivalent to a logical font with the following properties: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | A font that is guaranteed to be available in the operating system. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | The default font that is provided by the graphics device driver for the current output device. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | The default palette that is defined for the current output device. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | A fixed-width font that is guaranteed to be available in the operating system. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | A fixed-width font that is guaranteed to be available in the operating system. |
| [DC_BRUSH](#DC-BRUSH) | The solid-color brush that is currently selected in the playback device context |
| [DC_PEN](#DC-PEN) | The solid-color pen that is currently selected in the playback device context |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


A white, solid-color brush that is equivalent to a logical brush (LogBrushEx object, section 2.2.12) with the following properties: BrushStyle: BS\_SOLID (WMF BrushStyle enumeration, [MS-WMF] section 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef object, [MS-WMF] section 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


A light gray, solid-color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


A gray, solid-color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


A dark gray, solid color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


A black, solid color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


A null brush that is equivalent to a logical brush with the following properties: BrushStyle: BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


A white, solid-color pen that is equivalent to a logical pen (LogPen object, section 2.2.19) with the following properties: PenStyle: PS\_COSMETIC + PS\_SOLID (PenStyle enumeration, section 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef object).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


A black, solid-color pen that is equivalent to a logical pen with the following properties: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


A null pen that is equivalent to a logical pen with the following properties: PenStyle: PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


A fixed-width, OEM character set font that is equivalent to a logical font (LogFont object, section 2.2.13) with the following properties: Charset: OEM\_CHARSET (WMF CharacterSet enumeration, [MS-WMF] section 2.1.1.5) PitchAndFamily: FF\_DONTCARE (WMF FamilyFont enumeration, [MS-WMF] section 2.1.1.8) + FIXED\_PITCH (WMF PitchFont enumeration, [MS-WMF] section 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


A fixed-width font that is equivalent to a logical font with the following properties: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


A variable-width font that is equivalent to a logical font with the following properties: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


A font that is guaranteed to be available in the operating system. The actual font that is specified by this value is implementation-dependent

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


The default font that is provided by the graphics device driver for the current output device. The actual font that is specified by this value is implementation-dependent

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


The default palette that is defined for the current output device. The actual palette that is specified by this value is implementation-dependent

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


A fixed-width font that is guaranteed to be available in the operating system. The actual font that is specified by this value is implementation-dependent

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


A fixed-width font that is guaranteed to be available in the operating system. The actual font that is specified by this value is implementation-dependent

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


The solid-color brush that is currently selected in the playback device context

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


The solid-color pen that is currently selected in the playback device context

