---
title: WmfTextAlignmentModeFlags
second_title: Aspose.Imaging para la referencia de la API de .NET
description: TextAlignmentMode Los indicadores especifican la relación entre un punto de referencia y un rectángulo delimitador para la alineación del texto. Estos indicadores se pueden combinar para especificar varias opciones con la restricción de que solo se puede elegir un indicador que altere la posición del dibujo en el contexto del dispositivo de reproducción . La alineación horizontal del texto se realiza cuando la fuente tiene una línea de base horizontal predeterminada.
type: docs
weight: 8350
url: /es/net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
## WmfTextAlignmentModeFlags enumeration

TextAlignmentMode Los indicadores especifican la relación entre un punto de referencia y un rectángulo delimitador para la alineación del texto. Estos indicadores se pueden combinar para especificar varias opciones, con la restricción de que solo se puede elegir un indicador que altere la posición del dibujo en el contexto del dispositivo de reproducción . La alineación horizontal del texto se realiza cuando la fuente tiene una línea de base horizontal predeterminada.

```csharp
[Flags]
public enum WmfTextAlignmentModeFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Noupdatecp | `0` | La posición del dibujo en el contexto del dispositivo de reproducción NO DEBE actualizarse después de cada llamada de salida de texto . El punto de referencia DEBE pasarse a la función de salida de texto. |
| Left | `0` | El punto de referencia DEBE estar en el borde izquierdo del rectángulo delimitador. |
| Top | `0` | El punto de referencia DEBE estar en el borde superior del rectángulo delimitador. |
| Updatecp | `1` | La posición del dibujo en el contexto del dispositivo de reproducción DEBE actualizarse después de cada llamada de salida text . DEBE utilizarse como punto de referencia. |
| Right | `2` | El punto de referencia DEBE estar en el borde derecho del rectángulo delimitador. |
| Center | `6` | El punto de referencia DEBE estar alineado horizontalmente con el centro del rectángulo delimitador. |
| Bottom | `8` | El punto de referencia DEBE estar en el borde inferior del rectángulo delimitador. |
| Baseline | `18` | El punto de referencia DEBE estar en la línea base del texto. |
| Rtlreading | `100` | El texto DEBE estar dispuesto en el orden de lectura de derecha a izquierda, en lugar del orden predeterminado de izquierda a derecha. Esto DEBERÍA aplicarse solo cuando la fuente definida en el contexto del dispositivo playback sea hebrea o árabe. |
| Horizontal | `6` | Representa conjuntos de algin de texto horizontal (Izquierda &#x7C; Derecha &#x7C; Centro) |
| Vertical | `18` | Representa conjuntos de alineación de texto vertical (Superior &#x7C; Inferior &#x7C; Línea base) |

### Observaciones

Las banderas TextAlignmentMode especifican tres componentes diferentes de alineación de texto: - La posición horizontal del punto de referencia está determinada por TA_RIGHT y TA_CENTER; si esos bits están claros, la alineación DEBE ser TA_IZQUIERDA. - La posición vertical del punto de referencia está determinada por TA_BOTTOM y TA_BASELINE; si esos bits están claros, la alineación DEBE ser TA_TOP. - Si actualizar la posición de salida en el contexto del dispositivo de reproducción después de que la salida de texto sea determinada por TA_UPDATECP; si ese bit está limpio, la posición NO DEBE actualizarse. Esta es la razón para definir tres valores cero diferentes en la enumeración; representan los estados predeterminados de los tres componentes de la alineación del texto.

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
