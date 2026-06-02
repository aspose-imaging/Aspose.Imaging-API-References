---
title: "EmfStockObject"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración StockObject especifica los índices de objetos gráficos lógicos predefinidos que pueden usarse en operaciones gráficas. Las estructuras específicas de los objetos de stock dependen de la implementación, sin embargo, las propiedades de los objetos de stock DEBEN ser equivalentes a las propiedades de los objetos creados explícitamente del mismo tipo."
type: docs
weight: 42
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

La enumeración StockObject especifica los índices de objetos gráficos lógicos predefinidos que pueden usarse en operaciones gráficas. Las estructuras específicas de los objetos de stock dependen de la implementación; sin embargo, las propiedades de los objetos de stock DEBEN ser equivalentes a las propiedades de los objetos creados explícitamente del mismo tipo. Estas propiedades se especifican, cuando es posible, para los objetos de stock definidos en esta enumeración.
## Campos

| Campo | Descripción |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | Un pincel blanco de color sólido que es equivalente a un pincel lógico (objeto LogBrushEx, sección 2.2.12) con las siguientes propiedades: BrushStyle: BS\_SOLID (enumeración BrushStyle de WMF, [MS-WMF] sección 2.1.1.4) Color: 0x00FFFFFF (objeto ColorRef de WMF, [MS-WMF] sección 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | Un pincel de color sólido gris claro que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | Un pincel gris de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | Un pincel gris oscuro de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | Un pincel negro de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | Un pincel nulo que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | Un lápiz blanco de color sólido que es equivalente a un lápiz lógico (objeto LogPen, sección 2.2.19) con las siguientes propiedades: PenStyle: PS\_COSMETIC + PS\_SOLID (enumeración PenStyle, sección 2.1.25) ColorRef: 0x00FFFFFF (objeto WMF ColorRef). |
| [BLACK_PEN](#BLACK-PEN) | Un lápiz negro de color sólido que es equivalente a un lápiz lógico con las siguientes propiedades: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | Un lápiz nulo que es equivalente a un lápiz lógico con las siguientes propiedades: PenStyle: PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | Una fuente de ancho fijo, conjunto de caracteres OEM, que es equivalente a una fuente lógica (objeto LogFont, sección 2.2.13) con las siguientes propiedades: Charset: OEM\_CHARSET (enumeración WMF CharacterSet, [MS-WMF] sección 2.1.1.5) PitchAndFamily: FF\_DONTCARE (enumeración WMF FamilyFont, [MS-WMF] sección 2.1.1.8) + FIXED\_PITCH (enumeración WMF PitchFont, [MS-WMF] sección 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | Una fuente de ancho fijo que es equivalente a una fuente lógica con las siguientes propiedades: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | Una fuente de ancho variable que es equivalente a una fuente lógica con las siguientes propiedades: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | Una fuente que se garantiza que está disponible en el sistema operativo. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | La fuente predeterminada que proporciona el controlador del dispositivo gráfico para el dispositivo de salida actual. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | La paleta predeterminada que se define para el dispositivo de salida actual. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | Una fuente de ancho fijo que se garantiza que está disponible en el sistema operativo. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | Una fuente de ancho fijo que se garantiza que está disponible en el sistema operativo. |
| [DC_BRUSH](#DC-BRUSH) | El pincel de color sólido que está actualmente seleccionado en el contexto del dispositivo de reproducción |
| [DC_PEN](#DC-PEN) | El lápiz de color sólido que está actualmente seleccionado en el contexto del dispositivo de reproducción |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


Un pincel blanco de color sólido que es equivalente a un pincel lógico (objeto LogBrushEx, sección 2.2.12) con las siguientes propiedades: BrushStyle: BS\_SOLID (enumeración BrushStyle de WMF, [MS-WMF] sección 2.1.1.4) Color: 0x00FFFFFF (objeto ColorRef de WMF, [MS-WMF] sección 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


Un pincel de color sólido gris claro que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


Un pincel gris de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


Un pincel gris oscuro de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


Un pincel negro de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


Un pincel nulo que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


Un lápiz blanco de color sólido que es equivalente a un lápiz lógico (objeto LogPen, sección 2.2.19) con las siguientes propiedades: PenStyle: PS\_COSMETIC + PS\_SOLID (enumeración PenStyle, sección 2.1.25) ColorRef: 0x00FFFFFF (objeto WMF ColorRef).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


Un lápiz negro de color sólido que es equivalente a un lápiz lógico con las siguientes propiedades: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


Un lápiz nulo que es equivalente a un lápiz lógico con las siguientes propiedades: PenStyle: PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


Una fuente de ancho fijo, conjunto de caracteres OEM, que es equivalente a una fuente lógica (objeto LogFont, sección 2.2.13) con las siguientes propiedades: Charset: OEM\_CHARSET (enumeración WMF CharacterSet, [MS-WMF] sección 2.1.1.5) PitchAndFamily: FF\_DONTCARE (enumeración WMF FamilyFont, [MS-WMF] sección 2.1.1.8) + FIXED\_PITCH (enumeración WMF PitchFont, [MS-WMF] sección 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


Una fuente de ancho fijo que es equivalente a una fuente lógica con las siguientes propiedades: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


Una fuente de ancho variable que es equivalente a una fuente lógica con las siguientes propiedades: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


Una fuente que se garantiza que está disponible en el sistema operativo. La fuente real especificada por este valor depende de la implementación

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


La fuente predeterminada que proporciona el controlador del dispositivo gráfico para el dispositivo de salida actual. La fuente real especificada por este valor depende de la implementación

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


La paleta predeterminada que se define para el dispositivo de salida actual. La paleta real especificada por este valor depende de la implementación

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


Una fuente de ancho fijo que se garantiza que está disponible en el sistema operativo. La fuente real especificada por este valor depende de la implementación

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


Una fuente de ancho fijo que se garantiza que está disponible en el sistema operativo. La fuente real especificada por este valor depende de la implementación

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


El pincel de color sólido que está actualmente seleccionado en el contexto del dispositivo de reproducción

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


El lápiz de color sólido que está actualmente seleccionado en el contexto del dispositivo de reproducción

