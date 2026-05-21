---
title: "EmfPlusStringFormatFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los indicadores StringFormat especifican opciones para el diseño de texto gráfico, incluyendo dirección, recorte y manejo de fuentes."
type: docs
weight: 50
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

Los indicadores StringFormat especifican opciones para el diseño de texto gráfico, incluyendo dirección, recorte y manejo de fuentes. Estos indicadores pueden combinarse para especificar múltiples opciones.
## Campos

| Campo | Descripción |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | Si está establecido, el orden de lectura de la cadena DEBERÍA ser de derecha a izquierda. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | Si está establecido, las líneas individuales de texto DEBERÍAN dibujarse verticalmente en el dispositivo de visualización. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | Si está establecido, se DEBE permitir que partes de los caracteres sobresalgan del rectángulo de diseño de texto. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | Si está establecido, los caracteres de control DEBERÍAN aparecer en la salida como glifos Unicode representativos. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | Si está establecido, se DEBERÍA usar una fuente alternativa para los caracteres que no están soportados en la fuente solicitada. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | Si está establecido, el espacio al final de cada línea DEBE incluirse en las mediciones de la longitud de la cadena. |
| [StringFormatNoWrap](#StringFormatNoWrap) | Si está establecido, una cadena que se extienda más allá del final del rectángulo de diseño de texto NO DEBE envolver a la siguiente línea. |
| [StringFormatLineLimit](#StringFormatLineLimit) | Si está establecido, las líneas completas de texto DEBERÍAN emitirse y NO DEBERÍAN recortarse por el rectángulo de diseño de la cadena. |
| [StringFormatNoClip](#StringFormatNoClip) | Si está establecido, el texto que se extienda fuera del rectángulo de diseño de la cadena DEBERÍA poder mostrarse. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | Este indicador PUEDE usarse para especificar un proceso específico de implementación para renderizar texto. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


Si está establecido, el orden de lectura de la cadena DEBERÍA ser de derecha a izquierda. Para texto horizontal, esto significa que los caracteres se leen de derecha a izquierda. Para texto vertical, esto significa que las columnas se leen de derecha a izquierda. Si está desactivado, el texto horizontal o vertical DEBERÍA leerse de izquierda a derecha.

--------------------

El diseño de texto gráfico se especifica mediante objetos [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat).

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


Si está establecido, las líneas individuales de texto DEBERÍAN dibujarse verticalmente en el dispositivo de visualización. Si está desactivado, las líneas individuales de texto DEBERÍAN dibujarse horizontalmente, con cada nueva línea debajo de la anterior.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


Si está establecido, se DEBE permitir que partes de los caracteres sobresalgan del rectángulo de diseño de texto. Si está desactivado, los caracteres que sobresalgan de los límites del rectángulo de diseño de texto DEBEN reposicionarse para evitar el sobresalido. Un carácter en cursiva, "f", es un ejemplo de un carácter que puede tener partes sobresalientes.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


Si está establecido, los caracteres de control DEBERÍAN aparecer en la salida como glifos Unicode representativos.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


Si está establecido, se DEBERÍA usar una fuente alternativa para los caracteres que no están soportados en la fuente solicitada. Si está desactivado, un carácter que falta en la fuente solicitada DEBERÍA aparecer como un carácter de "fuente faltante", que PUEDE ser un cuadrado abierto.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


Si está establecido, el espacio al final de cada línea DEBE incluirse en las mediciones de la longitud de la cadena. Si está desactivado, el espacio al final de cada línea DEBE excluirse de las mediciones de la longitud de la cadena.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


Si está establecido, una cadena que se extienda más allá del final del rectángulo de diseño de texto NO DEBE envolver a la siguiente línea. Si está desactivado, una cadena que se extienda más allá del final del rectángulo de diseño de texto DEBE romperse en el último límite de palabra dentro del rectángulo delimitador, y el resto de la cadena DEBE envolver a la siguiente línea.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


Si está establecido, las líneas completas de texto DEBERÍAN emitirse y NO DEBERÍAN recortarse por el rectángulo de diseño de la cadena. Si está desactivado, el diseño de texto DEBERÍA continuar hasta que todas las líneas se emitan, o hasta que líneas adicionales no sean visibles como resultado del recorte. Este indicador puede usarse tanto para negar como para permitir que una línea de texto quede parcialmente oscurecida por un rectángulo de diseño que no sea múltiplo de la altura de línea. Para que todo el texto sea visible, el rectángulo de diseño debe ser al menos tan alto como la altura de una línea.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


Si está establecido, el texto que se extienda fuera del rectángulo de diseño de la cadena DEBERÍA poder mostrarse. Si está desactivado, todo el texto que se extienda fuera del rectángulo de diseño DEBERÍA recortarse.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


Este indicador PUEDE usarse para especificar un proceso específico de implementación para renderizar texto.

