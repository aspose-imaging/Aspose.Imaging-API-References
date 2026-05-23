---
title: "EmfPlusStringFormatFlags Enumeración"
type: docs
weight: 410
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---

Los indicadores StringFormat especifican opciones para el diseño de texto gráfico, incluyendo dirección, recorte y manejo de fuentes. Estos indicadores pueden combinarse para especificar múltiples opciones.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusStringFormatFlags

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| STRING_FORMAT_BYPASS_GDI | Esta bandera PUEDE usarse para especificar un proceso específico de implementación para renderizar texto. |
| STRING_FORMAT_DIRECTION_RIGHT_TO_LEFT | Si está establecido, el orden de lectura de la cadena DEBERÍA ser de derecha a izquierda. Para texto horizontal, esto significa que los caracteres se leen de derecha a izquierda. Para texto vertical, esto significa que las columnas se leen de derecha a izquierda.<br/>            Si se desactiva, el texto horizontal o vertical DEBERÍA leerse de izquierda a derecha. |
| STRING_FORMAT_DIRECTION_VERTICAL | Si está establecido, las líneas individuales de texto DEBERÁN dibujarse verticalmente en el dispositivo de visualización.<br/>            Si se desactiva, las líneas individuales de texto DEBERÁN dibujarse horizontalmente, con cada nueva línea debajo de la línea anterior. |
| STRING_FORMAT_DISPLAY_FORMAT_CONTROL | Si está establecido, los caracteres de control DEBERÁN aparecer en la salida como glifos Unicode representativos. |
| STRING_FORMAT_LINE_LIMIT | Si está establecido, las líneas completas de texto DEBERÁN emitirse y NO DEBERÁN ser recortadas por el rectángulo de diseño de la cadena.<br/>            Si se desactiva, el diseño del texto DEBERÁ continuar hasta que se emitan todas las líneas, o hasta que líneas adicionales no sean visibles como resultado del recorte.<br/>            Esta bandera puede usarse tanto para negar como para permitir que una línea de texto sea parcialmente oculta por un rectángulo de diseño que no sea múltiplo de la altura de línea. Para que todo el texto sea visible, el rectángulo de diseño debe ser al menos tan alto como la altura de una línea. |
| STRING_FORMAT_MEASURE_TRAILING_SPACES | Si está activado, el espacio al final de cada línea DEBE incluirse en las mediciones de la longitud de la cadena.<br/>            Si está desactivado, el espacio al final de cada línea DEBE excluirse de las mediciones de la longitud de la cadena. |
| STRING_FORMAT_NO_CLIP | Si está activado, se DEBERÍA permitir que el texto que se extiende fuera del rectángulo de diseño de la cadena se muestre.<br/>            Si está desactivado, todo el texto que se extiende fuera del rectángulo de diseño SE DEBERÍA recortar. |
| STRING_FORMAT_NO_FIT_BLACK_BOX | Si está activado, se DEBE permitir que partes de los caracteres sobresalgan del rectángulo de diseño del texto.<br/>            Si está desactivado, los caracteres que sobresalgan de los límites del rectángulo de diseño del texto DEBEN ser reubicados para evitar el sobresalimiento.<br/>            Una \"f\" cursiva es un ejemplo de un carácter que puede tener partes sobresalientes. |
| STRING_FORMAT_NO_FONT_FALLBACK | Si está activado, se DEBERÍA usar una fuente alternativa para los caracteres que no están soportados en la fuente solicitada.<br/>            Si está desactivado, un carácter ausente de la fuente solicitada DEBERÍA aparecer como un carácter de \"fuente faltante\", que PUEDE ser un cuadrado abierto. |
| STRING_FORMAT_NO_WRAP | Si está activado, una cadena que se extienda más allá del final del rectángulo de diseño del texto NO DEBE envolver a la siguiente línea.<br/>            Si está desactivado, una cadena que se extienda más allá del final del rectángulo de diseño del texto DEBE romperse en el último límite de palabra dentro del rectángulo delimitador, y el resto de la cadena DEBE envolver a la siguiente línea. |
