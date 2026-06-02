---
title: "WmfTextAlignmentModeFlags Enumeración"
type: docs
weight: 270
url: /es/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---

Los indicadores TextAlignmentMode especifican la relación entre un punto de referencia y un rectángulo delimitador<br/>                para la alineación de texto. Estos indicadores pueden combinarse para especificar múltiples opciones, con la<br/>                restricción de que solo se puede elegir un indicador que altere la posición de dibujo en el contexto del dispositivo de reproducción<br/>                .<br/>                La alineación horizontal del texto se realiza cuando la fuente tiene una línea base predeterminada horizontal.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfTextAlignmentModeFlags

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| BASELINE | El punto de referencia DEBE estar en la línea base del texto. |
| BOTTOM | El punto de referencia DEBE estar en el borde inferior del rectángulo delimitador. |
| CENTER | El punto de referencia DEBE alinearse horizontalmente con el centro del rectángulo delimitador. |
| HORIZONTAL | Representa conjuntos de alineación de texto horizontal (Izquierda | Derecha | Centro) |
| IZQUIERDA | El punto de referencia DEBE estar en el borde izquierdo del rectángulo delimitador. |
| NOUPDATECP | La posición de dibujo en el contexto del dispositivo de reproducción NO DEBE actualizarse después de cada<br/>                llamada de salida de texto. El punto de referencia DEBE pasarse a la función de salida de texto. |
| DERECHA | El punto de referencia DEBE estar en el borde derecho del rectángulo delimitador. |
| RTLREADING | El texto DEBE disponerse en orden de lectura de derecha a izquierda, en lugar del orden predeterminado de izquierda a derecha. Esto DEBERÍA<br/>                aplicarse solo cuando la fuente definida en el contexto del dispositivo de reproducción sea hebreo o árabe. |
| SUPERIOR | El punto de referencia DEBE estar en el borde superior del rectángulo delimitador. |
| UPDATECP | La posición de dibujo en el contexto del dispositivo de reproducción DEBE actualizarse después de cada texto<br/>                llamada de salida. DEBE usarse como el punto de referencia. |
| VERTICAL | Representa conjuntos de alineación de texto vertical (Superior | Inferior | Línea base) |
