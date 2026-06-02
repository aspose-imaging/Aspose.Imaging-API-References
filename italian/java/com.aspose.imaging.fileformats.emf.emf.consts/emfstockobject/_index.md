---
title: "EmfStockObject"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione StockObject specifica gli indici degli oggetti grafici logici predefiniti che possono essere usati nelle operazioni grafiche. Le strutture specifiche degli oggetti stock dipendono dall'implementazione, tuttavia le proprietà degli oggetti stock DEVONO essere equivalenti alle proprietà degli oggetti creati esplicitamente dello stesso tipo."
type: docs
weight: 42
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

L'enumerazione StockObject specifica gli indici degli oggetti grafici logici predefiniti che possono essere usati nelle operazioni grafiche. Le strutture specifiche degli oggetti stock dipendono dall'implementazione; tuttavia, le proprietà degli oggetti stock DEVONO essere equivalenti alle proprietà degli oggetti creati esplicitamente dello stesso tipo. Queste proprietà sono specificate, dove possibile, per gli oggetti stock definiti in questa enumerazione.
## Campi

| Campo | Descrizione |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | Un pennello bianco a colore solido equivalente a un pennello logico (oggetto LogBrushEx, sezione 2.2.12) con le seguenti proprietà: BrushStyle: BS\_SOLID (enumerazione WMF BrushStyle, [MS-WMF] sezione 2.1.1.4) Color: 0x00FFFFFF (oggetto WMF ColorRef, [MS-WMF] sezione 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | Un pennello di colore solido grigio chiaro equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | Un pennello di colore solido grigio equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | Un pennello di colore solido grigio scuro equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | Un pennello di colore solido nero equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | Un pennello nullo equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | Una penna di colore solido bianca equivalente a una penna logica (oggetto LogPen, sezione 2.2.19) con le seguenti proprietà: PenStyle: PS\_COSMETIC + PS\_SOLID (enumerazione PenStyle, sezione 2.1.25) ColorRef: 0x00FFFFFF (oggetto WMF ColorRef). |
| [BLACK_PEN](#BLACK-PEN) | Una penna di colore solido nero equivalente a una penna logica con le seguenti proprietà: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | Una penna nulla equivalente a una penna logica con le seguenti proprietà: PenStyle: PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | Un carattere a larghezza fissa, set di caratteri OEM equivalente a un carattere logico (oggetto LogFont, sezione 2.2.13) con le seguenti proprietà: Charset: OEM\_CHARSET (enumerazione WMF CharacterSet, [MS-WMF] sezione 2.1.1.5) PitchAndFamily: FF\_DONTCARE (enumerazione WMF FamilyFont, [MS-WMF] sezione 2.1.1.8) + FIXED\_PITCH (enumerazione WMF PitchFont, [MS-WMF] sezione 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | Un carattere a larghezza fissa equivalente a un carattere logico con le seguenti proprietà: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | Un carattere a larghezza variabile equivalente a un carattere logico con le seguenti proprietà: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | Un carattere garantito disponibile nel sistema operativo. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | Il carattere predefinito fornito dal driver del dispositivo grafico per il dispositivo di output corrente. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | La tavolozza predefinita definita per il dispositivo di output corrente. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | Un carattere a larghezza fissa garantito disponibile nel sistema operativo. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | Un carattere a larghezza fissa garantito disponibile nel sistema operativo. |
| [DC_BRUSH](#DC-BRUSH) | Il pennello di colore solido attualmente selezionato nel contesto del dispositivo di riproduzione |
| [DC_PEN](#DC-PEN) | La penna di colore solido attualmente selezionata nel contesto del dispositivo di riproduzione |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


Un pennello bianco a colore solido equivalente a un pennello logico (oggetto LogBrushEx, sezione 2.2.12) con le seguenti proprietà: BrushStyle: BS\_SOLID (enumerazione WMF BrushStyle, [MS-WMF] sezione 2.1.1.4) Color: 0x00FFFFFF (oggetto WMF ColorRef, [MS-WMF] sezione 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


Un pennello di colore solido grigio chiaro equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


Un pennello di colore solido grigio equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


Un pennello di colore solido grigio scuro equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


Un pennello di colore solido nero equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


Un pennello nullo equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


Una penna di colore solido bianca equivalente a una penna logica (oggetto LogPen, sezione 2.2.19) con le seguenti proprietà: PenStyle: PS\_COSMETIC + PS\_SOLID (enumerazione PenStyle, sezione 2.1.25) ColorRef: 0x00FFFFFF (oggetto WMF ColorRef).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


Una penna di colore solido nero equivalente a una penna logica con le seguenti proprietà: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


Una penna nulla equivalente a una penna logica con le seguenti proprietà: PenStyle: PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


Un carattere a larghezza fissa, set di caratteri OEM equivalente a un carattere logico (oggetto LogFont, sezione 2.2.13) con le seguenti proprietà: Charset: OEM\_CHARSET (enumerazione WMF CharacterSet, [MS-WMF] sezione 2.1.1.5) PitchAndFamily: FF\_DONTCARE (enumerazione WMF FamilyFont, [MS-WMF] sezione 2.1.1.8) + FIXED\_PITCH (enumerazione WMF PitchFont, [MS-WMF] sezione 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


Un carattere a larghezza fissa equivalente a un carattere logico con le seguenti proprietà: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


Un carattere a larghezza variabile equivalente a un carattere logico con le seguenti proprietà: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


Un carattere garantito disponibile nel sistema operativo. Il carattere effettivo specificato da questo valore dipende dall'implementazione

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


Il carattere predefinito fornito dal driver del dispositivo grafico per il dispositivo di output corrente. Il carattere effettivo specificato da questo valore dipende dall'implementazione

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


La tavolozza predefinita definita per il dispositivo di output corrente. La tavolozza effettiva specificata da questo valore dipende dall'implementazione

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


Un carattere a larghezza fissa garantito disponibile nel sistema operativo. Il carattere effettivo specificato da questo valore dipende dall'implementazione

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


Un carattere a larghezza fissa garantito disponibile nel sistema operativo. Il carattere effettivo specificato da questo valore dipende dall'implementazione

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


Il pennello di colore solido attualmente selezionato nel contesto del dispositivo di riproduzione

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


La penna di colore solido attualmente selezionata nel contesto del dispositivo di riproduzione

