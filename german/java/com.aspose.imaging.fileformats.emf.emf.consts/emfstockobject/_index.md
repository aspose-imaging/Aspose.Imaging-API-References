---
title: "EmfStockObject"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die StockObject‑Aufzählung spezifiziert die Indizes vordefinierter logischer Grafikobjekte, die in Grafikoperationen verwendet werden können. Die spezifischen Strukturen von Stock‑Objekten sind implementierungsabhängig, jedoch sollten die Eigenschaften von Stock‑Objekten den Eigenschaften von explizit erstellten Objekten desselben Typs entsprechen."
type: docs
weight: 42
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

Die StockObject‑Aufzählung spezifiziert die Indizes vordefinierter logischer Grafikobjekte, die in Grafikoperationen verwendet werden können. Die spezifischen Strukturen von Stock‑Objekten sind implementierungsabhängig; jedoch sollten die Eigenschaften von Stock‑Objekten den Eigenschaften von explizit erstellten Objekten desselben Typs entsprechen. Diese Eigenschaften werden, wo möglich, für die in dieser Aufzählung definierten Stock‑Objekte angegeben.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | Ein weißer, einfarbiger Pinsel, der einem logischen Pinsel (LogBrushEx‑Objekt, Abschnitt 2.2.12) entspricht und die folgenden Eigenschaften aufweist: BrushStyle: BS\_SOLID (WMF BrushStyle‑Aufzählung, [MS-WMF] Abschnitt 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef‑Objekt, [MS-WMF] Abschnitt 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | Ein hellgrauer, einfarbiger Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | Ein grauer, einfarbiger Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | Ein dunkelgrauer, einfarbiger Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | Ein schwarzer, einfarbiger Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | Ein Null-Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | Ein weißer, einfarbiger Stift, der einem logischen Stift (LogPen-Objekt, Abschnitt 2.2.19) mit den folgenden Eigenschaften entspricht: PenStyle: PS\_COSMETIC + PS\_SOLID (PenStyle‑Aufzählung, Abschnitt 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef‑Objekt). |
| [BLACK_PEN](#BLACK-PEN) | Ein schwarzer, einfarbiger Stift, der einem logischen Stift mit den folgenden Eigenschaften entspricht: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | Ein Null-Stift, der einem logischen Stift mit den folgenden Eigenschaften entspricht: PenStyle: PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | Eine festbreite, OEM‑Zeichensatz‑Schriftart, die einer logischen Schriftart (LogFont‑Objekt, Abschnitt 2.2.13) mit den folgenden Eigenschaften entspricht: Charset: OEM\_CHARSET (WMF CharacterSet‑Aufzählung, [MS-WMF] Abschnitt 2.1.1.5) PitchAndFamily: FF\_DONTCARE (WMF FamilyFont‑Aufzählung, [MS-WMF] Abschnitt 2.1.1.8) + FIXED\_PITCH (WMF PitchFont‑Aufzählung, [MS-WMF] Abschnitt 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | Eine festbreite Schriftart, die einer logischen Schriftart mit den folgenden Eigenschaften entspricht: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | Eine proportional breite Schriftart, die einer logischen Schriftart mit den folgenden Eigenschaften entspricht: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | Eine Schriftart, die im Betriebssystem garantiert verfügbar ist. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | Die Standardschriftart, die vom Grafikgerätetreiber für das aktuelle Ausgabegerät bereitgestellt wird. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | Die Standardpalette, die für das aktuelle Ausgabegerät definiert ist. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | Eine festbreite Schriftart, die im Betriebssystem garantiert verfügbar ist. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | Eine festbreite Schriftart, die im Betriebssystem garantiert verfügbar ist. |
| [DC_BRUSH](#DC-BRUSH) | Der einfarbige Pinsel, der derzeit im Wiedergabegerätekontext ausgewählt ist |
| [DC_PEN](#DC-PEN) | Der einfarbige Stift, der derzeit im Wiedergabegerätekontext ausgewählt ist |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


Ein weißer, einfarbiger Pinsel, der einem logischen Pinsel (LogBrushEx‑Objekt, Abschnitt 2.2.12) entspricht und die folgenden Eigenschaften aufweist: BrushStyle: BS\_SOLID (WMF BrushStyle‑Aufzählung, [MS-WMF] Abschnitt 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef‑Objekt, [MS-WMF] Abschnitt 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


Ein hellgrauer, einfarbiger Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


Ein grauer, einfarbiger Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


Ein dunkelgrauer, einfarbiger Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


Ein schwarzer, einfarbiger Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


Ein Null-Pinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


Ein weißer, einfarbiger Stift, der einem logischen Stift (LogPen-Objekt, Abschnitt 2.2.19) mit den folgenden Eigenschaften entspricht: PenStyle: PS\_COSMETIC + PS\_SOLID (PenStyle‑Aufzählung, Abschnitt 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef‑Objekt).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


Ein schwarzer, einfarbiger Stift, der einem logischen Stift mit den folgenden Eigenschaften entspricht: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


Ein Null-Stift, der einem logischen Stift mit den folgenden Eigenschaften entspricht: PenStyle: PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


Eine festbreite, OEM‑Zeichensatz‑Schriftart, die einer logischen Schriftart (LogFont‑Objekt, Abschnitt 2.2.13) mit den folgenden Eigenschaften entspricht: Charset: OEM\_CHARSET (WMF CharacterSet‑Aufzählung, [MS-WMF] Abschnitt 2.1.1.5) PitchAndFamily: FF\_DONTCARE (WMF FamilyFont‑Aufzählung, [MS-WMF] Abschnitt 2.1.1.8) + FIXED\_PITCH (WMF PitchFont‑Aufzählung, [MS-WMF] Abschnitt 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


Eine festbreite Schriftart, die einer logischen Schriftart mit den folgenden Eigenschaften entspricht: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


Eine proportional breite Schriftart, die einer logischen Schriftart mit den folgenden Eigenschaften entspricht: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


Eine Schriftart, die im Betriebssystem garantiert verfügbar ist. Die tatsächlich durch diesen Wert angegebene Schriftart ist implementierungsabhängig

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


Die Standardschriftart, die vom Grafikgerätetreiber für das aktuelle Ausgabegerät bereitgestellt wird. Die tatsächlich durch diesen Wert angegebene Schriftart ist implementierungsabhängig

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


Die Standardpalette, die für das aktuelle Ausgabegerät definiert ist. Die tatsächlich durch diesen Wert angegebene Palette ist implementierungsabhängig

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


Eine festbreite Schriftart, die im Betriebssystem garantiert verfügbar ist. Die tatsächlich durch diesen Wert angegebene Schriftart ist implementierungsabhängig

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


Eine festbreite Schriftart, die im Betriebssystem garantiert verfügbar ist. Die tatsächlich durch diesen Wert angegebene Schriftart ist implementierungsabhängig

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


Der einfarbige Pinsel, der derzeit im Wiedergabegerätekontext ausgewählt ist

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


Der einfarbige Stift, der derzeit im Wiedergabegerätekontext ausgewählt ist

