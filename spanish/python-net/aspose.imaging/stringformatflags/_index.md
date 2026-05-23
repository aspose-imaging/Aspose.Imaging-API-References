---
title: "Enumeración StringFormatFlags"
type: docs
weight: 11220
url: /es/python-net/aspose.imaging/stringformatflags/
---

Especifica la información de visualización y diseño para cadenas de texto.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormatFlags

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | El texto se muestra de derecha a izquierda. |
| DIRECTION_VERTICAL | El texto está alineado verticalmente. |
| DISPLAY_FORMAT_CONTROL | Los caracteres de control, como la marca de izquierda a derecha, se muestran en la salida con un glifo representativo. |
| EXACT_ALIGNMENT | La alineación exacta, relleno correcto GDI+ |
| FIT_BLACK_BOX | Se permite que partes de los caracteres sobresalgan del rectángulo de diseño de la cadena. Por defecto, los caracteres se reposicionan para evitar cualquier sobresaliente. |
| LINE_LIMIT | Solo se disponen líneas completas dentro del rectángulo de formato. De forma predeterminada, el diseño continúa hasta el final del texto, o hasta que no haya más líneas visibles como resultado del recorte, lo que ocurra primero.<br/>            Tenga en cuenta que la configuración predeterminada permite que la última línea quede parcialmente oculta por un rectángulo de formato que no es un múltiplo entero de la altura de línea. Para asegurarse de que solo se vean líneas completas,<br/>            especifique este valor y tenga cuidado de proporcionar un rectángulo de formato al menos tan alto como la altura de una línea. |
| MEASURE_TRAILING_SPACES | Incluye el espacio final al final de cada línea. De forma predeterminada, el rectángulo de límite devuelto por el método MeasureString excluye el espacio al final de cada línea. Establezca esta bandera para incluir ese espacio en la medición. |
| NO_CLIP | Se permite que se muestren las partes sobresalientes de los glifos y el texto sin envolver que se extienden fuera del rectángulo de formato. De forma predeterminada, todo el texto y las partes de los glifos que se extienden fuera del rectángulo de formato se recortan. |
| NO_FONT_FALLBACK | Se desactiva la sustitución por fuentes alternativas para los caracteres que no son compatibles con la fuente solicitada. Cualquier carácter faltante se muestra con el glifo faltante de la fuente, generalmente un cuadrado abierto. |
| NO_WRAP | Se desactiva el ajuste de texto entre líneas al formatear dentro de un rectángulo. Esta bandera se implica cuando se pasa un punto en lugar de un rectángulo, o cuando el rectángulo especificado tiene una longitud de línea cero. |
