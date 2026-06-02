---
title: "WmfTextAlignmentModeFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las banderas TextAlignmentMode especifican la relación entre un punto de referencia y un rectángulo delimitador para la alineación de texto."
type: docs
weight: 36
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

Las banderas TextAlignmentMode especifican la relación entre un punto de referencia y un rectángulo delimitador, para la alineación de texto. Estas banderas pueden combinarse para especificar múltiples opciones, con la restricción de que solo se puede elegir una bandera que altere la posición de dibujo en el contexto del dispositivo de reproducción. La alineación horizontal del texto se realiza cuando la fuente tiene una línea base predeterminada horizontal.

--------------------

Las banderas TextAlignmentMode especifican tres componentes diferentes de la alineación de texto: - La posición horizontal del punto de referencia se determina con TA\_RIGHT y TA\_CENTER; si esos bits están despejados, la alineación DEBE ser TA\_LEFT. - La posición vertical del punto de referencia se determina con TA\_BOTTOM y TA\_BASELINE; si esos bits están despejados, la alineación DEBE ser TA\_TOP. - Si se debe actualizar la posición de salida en el contexto del dispositivo de reproducción después de la salida de texto se determina con TA\_UPDATECP; si ese bit está despejado, la posición NO DEBE actualizarse. Esta es la razón para definir tres valores cero diferentes en la enumeración; representan los estados predeterminados de los tres componentes de la alineación de texto.
## Campos

| Campo | Descripción |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | La posición de dibujo en el contexto del dispositivo de reproducción NO DEBE actualizarse después de cada llamada de salida de texto. |
| [Left](#Left) | El punto de referencia DEBE estar en el borde izquierdo del rectángulo delimitador. |
| [Top](#Top) | El punto de referencia DEBE estar en el borde superior del rectángulo delimitador. |
| [Updatecp](#Updatecp) | La posición de dibujo en el contexto del dispositivo de reproducción DEBE actualizarse después de cada llamada de salida de texto. |
| [Right](#Right) | El punto de referencia DEBE estar en el borde derecho del rectángulo delimitador. |
| [Center](#Center) | El punto de referencia DEBE alinearse horizontalmente con el centro del rectángulo delimitador. |
| [Bottom](#Bottom) | El punto de referencia DEBE estar en el borde inferior del rectángulo delimitador. |
| [Baseline](#Baseline) | El punto de referencia DEBE estar en la línea base del texto. |
| [Rtlreading](#Rtlreading) | El texto DEBE disponerse en orden de lectura de derecha a izquierda, en lugar del orden predeterminado de izquierda a derecha. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Centro) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Línea base) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


La posición de dibujo en el contexto del dispositivo de reproducción NO DEBE actualizarse después de cada llamada de salida de texto. El punto de referencia DEBE pasarse a la función de salida de texto.

### Left {#Left}
```
public static final int Left
```


El punto de referencia DEBE estar en el borde izquierdo del rectángulo delimitador.

### Top {#Top}
```
public static final int Top
```


El punto de referencia DEBE estar en el borde superior del rectángulo delimitador.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


La posición de dibujo en el contexto del dispositivo de reproducción DEBE actualizarse después de cada llamada de salida de texto. DEBE usarse como el punto de referencia.

### Right {#Right}
```
public static final int Right
```


El punto de referencia DEBE estar en el borde derecho del rectángulo delimitador.

### Center {#Center}
```
public static final int Center
```


El punto de referencia DEBE alinearse horizontalmente con el centro del rectángulo delimitador.

### Bottom {#Bottom}
```
public static final int Bottom
```


El punto de referencia DEBE estar en el borde inferior del rectángulo delimitador.

### Baseline {#Baseline}
```
public static final int Baseline
```


El punto de referencia DEBE estar en la línea base del texto.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


El texto DEBE disponerse en orden de lectura de derecha a izquierda, en lugar del orden predeterminado de izquierda a derecha. Esto DEBERÍA aplicarse solo cuando la fuente definida en el contexto del dispositivo de reproducción sea hebreo o árabe.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Representa conjuntos de alineación horizontal de texto (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


Representa conjuntos de alineación vertical de texto (Top | Bottom | Baseline)

