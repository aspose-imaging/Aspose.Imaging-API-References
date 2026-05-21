---
title: "StringFormatFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica la información de visualización y diseño para cadenas de texto."
type: docs
weight: 113
url: /es/java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Especifica la información de visualización y diseño para cadenas de texto.
## Campos

| Campo | Descripción |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | El texto se muestra de derecha a izquierda. |
| [DirectionVertical](#DirectionVertical) | El texto está alineado verticalmente. |
| [FitBlackBox](#FitBlackBox) | Se permite que partes de los caracteres sobresalgan del rectángulo de diseño de la cadena. |
| [DisplayFormatControl](#DisplayFormatControl) | Los caracteres de control, como la marca de izquierda a derecha, se muestran en la salida con un glifo representativo. |
| [NoFontFallback](#NoFontFallback) | Se desactiva la alternativa a fuentes distintas para los caracteres no compatibles con la fuente solicitada. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Incluye el espacio final al final de cada línea. |
| [NoWrap](#NoWrap) | El ajuste de texto entre líneas al formatear dentro de un rectángulo está desactivado. |
| [LineLimit](#LineLimit) | Solo se disponen líneas completas en el rectángulo de formato. |
| [NoClip](#NoClip) | Se permite que se muestren partes sobresalientes de los glifos y texto sin ajustar que se extiendan fuera del rectángulo de formato. |
| [ExactAlignment](#ExactAlignment) | La alineación exacta, el relleno correcto GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


El texto se muestra de derecha a izquierda.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


El texto está alineado verticalmente.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Se permite que partes de los caracteres sobresalgan del rectángulo de diseño de la cadena. Por defecto, los caracteres se reposicionan para evitar cualquier sobresaliente.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Los caracteres de control, como la marca de izquierda a derecha, se muestran en la salida con un glifo representativo.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Se desactiva la alternativa a fuentes distintas para los caracteres no compatibles con la fuente solicitada. Cualquier carácter faltante se muestra con el glifo de falta de la fuente, usualmente un cuadrado abierto.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Incluye el espacio final al final de cada línea. Por defecto, el rectángulo de límite devuelto por el método MeasureString excluye el espacio al final de cada línea. Establezca esta bandera para incluir ese espacio en la medición.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


El ajuste de texto entre líneas al formatear dentro de un rectángulo está desactivado. Esta bandera se implica cuando se pasa un punto en lugar de un rectángulo, o cuando el rectángulo especificado tiene una longitud de línea cero.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Solo se disponen líneas completas en el rectángulo de formato. Por defecto, el diseño continúa hasta el final del texto, o hasta que no haya más líneas visibles como resultado del recorte, lo que ocurra primero. Tenga en cuenta que la configuración predeterminada permite que la última línea quede parcialmente oculta por un rectángulo de formato que no es un múltiplo exacto de la altura de la línea. Para garantizar que solo se vean líneas completas, especifique este valor y tenga cuidado de proporcionar un rectángulo de formato al menos tan alto como la altura de una línea.

### NoClip {#NoClip}
```
public static final int NoClip
```


Se permite que se muestren partes sobresalientes de los glifos y texto sin ajustar que se extiendan fuera del rectángulo de formato. Por defecto, todo el texto y las partes de los glifos que se extienden fuera del rectángulo de formato se recortan.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


La alineación exacta, el relleno correcto GDI+

