---
title: "EmfStockObject"
second_title: "Aspose.Imaging för Java API-referens"
description: "StockObject‑enumerationen specificerar index för fördefinierade logiska grafikobjekt som kan användas i grafikoperationer. De specifika strukturerna för stock‑objekt är implementationsberoende, men egenskaperna för stock‑objekt SKALL vara ekvivalenta med egenskaperna för explicit skapade objekt av samma typ."
type: docs
weight: 42
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

StockObject‑enumerationen specificerar index för fördefinierade logiska grafikobjekt som kan användas i grafikoperationer. De specifika strukturerna för stock‑objekt är implementationsberoende; dock SKALL egenskaperna för stock‑objekt vara ekvivalenta med egenskaperna för explicit skapade objekt av samma typ. Dessa egenskaper specificeras där det är möjligt för de stock‑objekt som definieras i denna enumeration.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | En vit, enfärgad pensel som är ekvivalent med en logisk pensel (LogBrushEx‑objekt, sektion 2.2.12) med följande egenskaper: BrushStyle: BS\_SOLID (WMF BrushStyle‑enumeration, [MS-WMF] sektion 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef‑objekt, [MS-WMF] sektion 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | En ljusgrå, enfärgad pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | En grå, enfärgad pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | En mörkgrå, enfärgad pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | En svart, enfärgad pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | En null-pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | En vit, enfärgad penna som är ekvivalent med en logisk penna (LogPen-objekt, avsnitt 2.2.19) med följande egenskaper: PenStyle: PS\_COSMETIC + PS\_SOLID (PenStyle‑enumeration, avsnitt 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef‑objekt). |
| [BLACK_PEN](#BLACK-PEN) | En svart, enfärgad penna som är ekvivalent med en logisk penna med följande egenskaper: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | En null-penna som är ekvivalent med en logisk penna med följande egenskaper: PenStyle: PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | Ett fastbredd, OEM-teckenuppsättnings teckensnitt som är ekvivalent med ett logiskt teckensnitt (LogFont-objekt, avsnitt 2.2.13) med följande egenskaper: Charset: OEM\_CHARSET (WMF CharacterSet‑enumeration, [MS-WMF] avsnitt 2.1.1.5) PitchAndFamily: FF\_DONTCARE (WMF FamilyFont‑enumeration, [MS-WMF] avsnitt 2.1.1.8) + FIXED\_PITCH (WMF PitchFont‑enumeration, [MS-WMF] avsnitt 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | Ett fastbredd teckensnitt som är ekvivalent med ett logiskt teckensnitt med följande egenskaper: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | Ett variabelbredd teckensnitt som är ekvivalent med ett logiskt teckensnitt med följande egenskaper: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | Ett teckensnitt som garanteras vara tillgängligt i operativsystemet. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | Standardteckensnittet som tillhandahålls av grafikdrivrutinen för den aktuella utmatningsenheten. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | Standardpaletten som definieras för den aktuella utmatningsenheten. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | Ett fastbredd teckensnitt som garanteras vara tillgängligt i operativsystemet. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | Ett fastbredd teckensnitt som garanteras vara tillgängligt i operativsystemet. |
| [DC_BRUSH](#DC-BRUSH) | Den enfärgade penseln som för närvarande är vald i uppspelningsenhetens kontext |
| [DC_PEN](#DC-PEN) | Den enfärgade pennan som för närvarande är vald i uppspelningsenhetens kontext |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


En vit, enfärgad pensel som är ekvivalent med en logisk pensel (LogBrushEx‑objekt, sektion 2.2.12) med följande egenskaper: BrushStyle: BS\_SOLID (WMF BrushStyle‑enumeration, [MS-WMF] sektion 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef‑objekt, [MS-WMF] sektion 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


En ljusgrå, enfärgad pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


En grå, enfärgad pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


En mörkgrå, enfärgad pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


En svart, enfärgad pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


En null-pensel som är ekvivalent med en logisk pensel med följande egenskaper: BrushStyle: BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


En vit, enfärgad penna som är ekvivalent med en logisk penna (LogPen-objekt, avsnitt 2.2.19) med följande egenskaper: PenStyle: PS\_COSMETIC + PS\_SOLID (PenStyle‑enumeration, avsnitt 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef‑objekt).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


En svart, enfärgad penna som är ekvivalent med en logisk penna med följande egenskaper: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


En null-penna som är ekvivalent med en logisk penna med följande egenskaper: PenStyle: PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


Ett fastbredd, OEM-teckenuppsättnings teckensnitt som är ekvivalent med ett logiskt teckensnitt (LogFont-objekt, avsnitt 2.2.13) med följande egenskaper: Charset: OEM\_CHARSET (WMF CharacterSet‑enumeration, [MS-WMF] avsnitt 2.1.1.5) PitchAndFamily: FF\_DONTCARE (WMF FamilyFont‑enumeration, [MS-WMF] avsnitt 2.1.1.8) + FIXED\_PITCH (WMF PitchFont‑enumeration, [MS-WMF] avsnitt 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


Ett fastbredd teckensnitt som är ekvivalent med ett logiskt teckensnitt med följande egenskaper: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


Ett variabelbredd teckensnitt som är ekvivalent med ett logiskt teckensnitt med följande egenskaper: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


Ett teckensnitt som garanteras vara tillgängligt i operativsystemet. Det faktiska teckensnittet som anges av detta värde är beroende av implementationen

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


Standardteckensnittet som tillhandahålls av grafikdrivrutinen för den aktuella utmatningsenheten. Det faktiska teckensnittet som anges av detta värde är beroende av implementationen

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


Standardpaletten som definieras för den aktuella utmatningsenheten. Den faktiska paletten som anges av detta värde är beroende av implementationen

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


Ett fastbredd teckensnitt som garanteras vara tillgängligt i operativsystemet. Det faktiska teckensnittet som anges av detta värde är beroende av implementationen

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


Ett fastbredd teckensnitt som garanteras vara tillgängligt i operativsystemet. Det faktiska teckensnittet som anges av detta värde är beroende av implementationen

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


Den enfärgade penseln som för närvarande är vald i uppspelningsenhetens kontext

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


Den enfärgade pennan som för närvarande är vald i uppspelningsenhetens kontext

