---
title: "EmfExtTextOutOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración ExtTextOutOptions especifica los parámetros que controlan varios aspectos de la salida de texto mediante los registros EMR_SMALLTEXTOUT sección 2.3.5.37 y en los objetos EmrText."
type: docs
weight: 19
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

La enumeración ExtTextOutOptions especifica parámetros que controlan varios aspectos de la salida de texto mediante registros EMR\\_SMALLTEXTOUT(sección 2.3.5.37) y en objetos EmrText.
## Campos

| Campo | Descripción |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | Este bit indica que el color de fondo actual DEBE usarse para rellenar el rectángulo |
| [ETO_CLIPPED](#ETO-CLIPPED) | Este bit indica que el texto DEBE recortarse al rectángulo. |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | Este bit indica que los códigos de los caracteres en una cadena de texto de salida son en realidad índices de los glifos de caracteres en una fuente TrueType. |
| [ETO_RTLREADING](#ETO-RTLREADING) | Este bit indica que el texto DEBE disponerse en orden de lectura de derecha a izquierda, en lugar del orden predeterminado de izquierda a derecha. |
| [ETO_NO_RECT](#ETO-NO-RECT) | Este bit indica que el registro no especifica un rectángulo delimitador para la salida de texto. |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | Este bit indica que los códigos de los caracteres en una cadena de texto de salida son de 8 bits, derivados de los bytes bajos de los códigos de caracteres Unicode UTF16-LE de 16 bits, en los que se asume que el byte alto es 0. |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | Este bit indica que, para mostrar números, DEBEN usarse los dígitos apropiados a la configuración regional. |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | Este bit indica que, para mostrar números, DEBEN usarse dígitos europeos. |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | Este bit indica que no se debe realizar ningún procesamiento especial del sistema operativo para la colocación de glifos en cadenas de derecha a izquierda; es decir, todo el posicionamiento de glifos DEBE ser gestionado por los registros de dibujo y de estado en el metafichero. |
| [ETO_PDY](#ETO-PDY) | Este bit indica que deben proporcionarse tanto los valores de desplazamiento horizontal como vertical de los caracteres. |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | Este bit está reservado y NO DEBE usarse. |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


Este bit indica que el color de fondo actual DEBE usarse para rellenar el rectángulo

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


Este bit indica que el texto DEBE recortarse al rectángulo.

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


Este bit indica que los códigos de los caracteres en una cadena de texto de salida son en realidad índices de los glifos de caracteres en una fuente TrueType. Los índices de glifos son específicos de la fuente, por lo que, para mostrar los caracteres correctos durante la reproducción, la fuente que se utiliza DEBE ser idéntica a la fuente utilizada para generar los índices.

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


Este bit indica que el texto DEBE disponerse en orden de lectura de derecha a izquierda, en lugar del orden predeterminado de izquierda a derecha. Esto DEBE aplicarse solo cuando la fuente seleccionada en el contexto del dispositivo de reproducción es hebreo o árabe

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


Este bit indica que el registro no especifica un rectángulo delimitador para la salida de texto.

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


Este bit indica que los códigos de los caracteres en una cadena de texto de salida son de 8 bits, derivados de los bytes bajos de los códigos de caracteres Unicode UTF16-LE de 16 bits, en los que se asume que el byte alto es 0.

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


Este bit indica que, para mostrar números, DEBEN usarse los dígitos apropiados a la configuración regional.

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


Este bit indica que, para mostrar números, DEBEN usarse dígitos europeos.

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


Este bit indica que no se debe realizar ningún procesamiento especial del sistema operativo para la colocación de glifos en cadenas de derecha a izquierda; es decir, todo el posicionamiento de glifos DEBE ser gestionado por los registros de dibujo y de estado en el metafichero.

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


Este bit indica que deben proporcionarse tanto los valores de desplazamiento horizontal como vertical de los caracteres.

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


Este bit está reservado y NO DEBE usarse.

