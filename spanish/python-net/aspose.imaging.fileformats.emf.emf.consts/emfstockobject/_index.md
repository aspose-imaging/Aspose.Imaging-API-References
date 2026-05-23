---
title: "Enumeración EmfStockObject"
type: docs
weight: 330
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---

La enumeración StockObject especifica los índices de objetos gráficos lógicos predefinidos <br/>            que pueden usarse en operaciones gráficas. Las estructuras específicas de los objetos de stock son <br/>            dependientes de la implementación; sin embargo, las propiedades de los objetos de stock SHOULD ser equivalentes a <br/>            las propiedades de los objetos creados explícitamente del mismo tipo. <br/>            Estas propiedades se especifican, cuando sea posible, para los objetos de stock definidos en esta enumeración.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStockObject

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| ANSI_FIXED_FONT | Una fuente de ancho fijo que equivale a una fuente lógica con las siguientes propiedades:<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | Una fuente de ancho variable que equivale a una fuente lógica con las siguientes propiedades:<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| BLACK_BRUSH | Un pincel negro de color sólido que equivale a un pincel lógico con las siguientes propiedades:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00000000 |
| BLACK_PEN | Un lápiz negro de color sólido que equivale a un lápiz lógico con las siguientes propiedades:<br/>            PenStyle: PS_COSMETIC + PS_SOLID<br/>            ColorRef: 0x00000000 |
| DC_BRUSH | El pincel de color sólido que está actualmente seleccionado en el contexto del dispositivo de reproducción |
| DC_PEN | El lápiz de color sólido que está actualmente seleccionado en el contexto del dispositivo de reproducción |
| DEFAULT_GUI_FONT | Una fuente de ancho fijo que se garantiza que está disponible en el sistema operativo. <br/>            La fuente real especificada por este valor depende de la implementación |
| DEFAULT_PALETTE | La paleta predeterminada que se define para el dispositivo de salida actual. <br/>            La paleta real especificada por este valor depende de la implementación |
| DEVICE_DEFAULT_FONT | La fuente predeterminada que proporciona el controlador del dispositivo gráfico para el dispositivo de salida actual. <br/>            La fuente real especificada por este valor depende de la implementación |
| DKGRAY_BRUSH | Un pincel gris oscuro, de color sólido, que es equivalente a un pincel lógico con las siguientes propiedades:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00404040 |
| GRAY_BRUSH | Un pincel gris, de color sólido, que es equivalente a un pincel lógico con las siguientes propiedades:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00808080 |
| LTGRAY_BRUSH | Un pincel gris claro, de color sólido, que es equivalente a un pincel lógico con las siguientes propiedades:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00C0C0C0 |
| NULL_BRUSH | Un pincel nulo que es equivalente a un pincel lógico con las siguientes propiedades:<br/>            BrushStyle: BS_NULL |
| NULL_PEN | Una pluma nula que es equivalente a una pluma lógica con las siguientes propiedades:<br/>            PenStyle: PS_NULL |
| OEM_FIXED_FONT | Una fuente de ancho fijo, conjunto de caracteres OEM, que es equivalente a una fuente lógica <br/>            (objeto LogFont, sección 2.2.13) con las siguientes propiedades:<br/>            Charset: OEM_CHARSET (enumeración WMF CharacterSet, [MS-WMF] sección 2.1.1.5)<br/>            PitchAndFamily: FF_DONTCARE (enumeración WMF FamilyFont, [MS-WMF] sección 2.1.1.8) <br/>            + FIXED_PITCH (enumeración WMF PitchFont, [MS-WMF] sección 2.1.24) |
| SYSTEM_FIXED_FONT | Una fuente de ancho fijo que se garantiza que está disponible en el sistema operativo. <br/>            La fuente real especificada por este valor depende de la implementación |
| SYSTEM_FONT | Una fuente que se garantiza que está disponible en el sistema operativo. <br/>            La fuente real especificada por este valor depende de la implementación |
| WHITE_BRUSH | Un pincel blanco, de color sólido, que es equivalente a un pincel lógico <br/>            (objeto LogBrushEx, sección 2.2.12) con las siguientes propiedades:<br/>            BrushStyle: BS_SOLID (enumeración WMF BrushStyle, [MS-WMF] sección 2.1.1.4)<br/>            Color: 0x00FFFFFF (objeto WMF ColorRef, [MS-WMF] sección 2.2.2.8) |
| WHITE_PEN | Una pluma blanca, de color sólido, que es equivalente a una pluma lógica (objeto LogPen, sección 2.2.19)<br/>            con las siguientes propiedades:<br/>            PenStyle: PS_COSMETIC + PS_SOLID (enumeración PenStyle, sección 2.1.25)<br/>            ColorRef: 0x00FFFFFF (objeto WMF ColorRef). |
