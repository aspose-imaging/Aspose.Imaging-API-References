---
title: EmfStockObject
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La enumeración StockObject especifica los índices de objetos gráficos lógicos predefinidos que se pueden utilizar en operaciones gráficas. Las estructuras específicas de los objetos de stock son dependientes de la implementación sin embargo las propiedades de los objetos comunes DEBERÍAN ser equivalentes a las propiedades de los objetos creados explícitamente del mismo tipo. Estas propiedades se especifican siempre que sea posible para los objetos de stock definidos en esta enumeración.
type: docs
weight: 2860
url: /es/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

La enumeración StockObject especifica los índices de objetos gráficos lógicos predefinidos que se pueden utilizar en operaciones gráficas. Las estructuras específicas de los objetos de stock son dependientes de la implementación; sin embargo, las propiedades de los objetos comunes DEBERÍAN ser equivalentes a las propiedades de los objetos creados explícitamente del mismo tipo. Estas propiedades se especifican siempre que sea posible para los objetos de stock definidos en esta enumeración.

```csharp
public enum EmfStockObject
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | Un pincel blanco de color sólido que es equivalente a un pincel lógico (objeto LogBrushEx, sección 2.2.12) con las siguientes propiedades: BrushStyle: BS_SOLID (enumeración WMF BrushStyle, [MS-WMF] sección 2.1.1.4) Color: 0x00FFFFFF (objeto WMF ColorRef, [MS-WMF] sección 2.2.2.8) |
| LTGRAY_BRUSH | `-2147483647` | Un pincel gris claro de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS_SOLID Color: 0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | Un pincel gris de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS_SOLID Color: 0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | Un pincel gris oscuro de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS_SOLID Color: 0x00404040 |
| BLACK_BRUSH | `-2147483644` | Un pincel negro de color sólido que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS_SOLID Color: 0x00000000 |
| NULL_BRUSH | `-2147483643` | Un pincel nulo que es equivalente a un pincel lógico con las siguientes propiedades: BrushStyle: BS_NULL |
| WHITE_PEN | `-2147483642` | Un lápiz blanco de color sólido equivalente a un lápiz lógico (objeto LogPen, sección 2.2.19) con las siguientes propiedades: PenStyle: PS_COSMETIC + PS_SOLID (enumeración PenStyle, sección 2.1.25) ColorRef: 0x00FFFFFF ( Objeto WMF ColorRef). |
| BLACK_PEN | `-2147483641` | Un lápiz negro de color sólido equivalente a un lápiz lógico con las siguientes propiedades: PenStyle: PS_COSMETIC + PS_SOLID ColorRef: 0x00000000 |
| NULL_PEN | `-2147483640` | Una pluma nula equivalente a una pluma lógica con las siguientes propiedades: PenStyle: PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | Una fuente de juego de caracteres OEM de ancho fijo que es equivalente a una fuente lógica (objeto LogFont, sección 2.2.13) con las siguientes propiedades: Charset: OEM_CHARSET (enumeración WMF CharacterSet, [MS-WMF] sección 2.1.1.5 ) PitchAndFamily: FF_DONTCARE (enumeración WMF FamilyFont, [MS-WMF] sección 2.1.1.8) + FIXED_PITCH (enumeración WMF PitchFont, [MS-WMF] sección 2.1.1.24) |
| ANSI_FIXED_FONT | `-2147483637` | Una fuente de ancho fijo que es equivalente a una fuente lógica con las siguientes propiedades: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | Una fuente de ancho variable que es equivalente a una fuente lógica con las siguientes propiedades: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | Una fuente que está garantizada para estar disponible en el sistema operativo. La fuente real especificada por este valor depende de la implementación |
| DEVICE_DEFAULT_FONT | `-2147483634` | La fuente predeterminada proporcionada por el controlador del dispositivo gráfico para el dispositivo de salida actual. La fuente real especificada por este valor depende de la implementación |
| DEFAULT_PALETTE | `-2147483633` | La paleta predeterminada que se define para el dispositivo de salida actual. La paleta real especificada por este valor depende de la implementación |
| SYSTEM_FIXED_FONT | `-2147483632` | Una fuente de ancho fijo que está garantizada para estar disponible en el sistema operativo. La fuente real especificada por este valor depende de la implementación |
| DEFAULT_GUI_FONT | `-2147483631` | Una fuente de ancho fijo que está garantizada para estar disponible en el sistema operativo. La fuente real especificada por este valor depende de la implementación |
| DC_BRUSH | `-2147483630` | El pincel de color sólido que está actualmente seleccionado en el contexto del dispositivo de reproducción |
| DC_PEN | `-2147483629` | La pluma de color sólido que está actualmente seleccionada en el contexto del dispositivo de reproducción |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
