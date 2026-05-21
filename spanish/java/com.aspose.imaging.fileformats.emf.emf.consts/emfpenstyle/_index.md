---
title: "EmfPenStyle"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración PenStyle define los atributos de los pinceles que pueden usarse en operaciones gráficas."
type: docs
weight: 34
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

La enumeración PenStyle define los atributos de los lápices que pueden usarse en operaciones gráficas. Un estilo de lápiz es una combinación de tipo de lápiz, estilo de línea, terminación de línea y unión de línea.
## Campos

| Campo | Descripción |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | Un tipo de lápiz que especifica una línea con un ancho de una unidad lógica y un estilo que es un color sólido. |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | Una terminación de línea que especifica extremos redondos. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | Una unión de línea que especifica uniones redondas. |
| [PS_SOLID](#PS-SOLID) | Un estilo de línea que es un color sólido. |
| [PS_DASH](#PS-DASH) | Un estilo de línea que es discontinuo. |
| [PS_DOT](#PS-DOT) | Un estilo de línea que es punteado. |
| [PS_DASHDOT](#PS-DASHDOT) | Un estilo de línea que consiste en guiones y puntos alternados. |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | Un estilo de línea que consiste en guiones y puntos dobles. |
| [PS_NULL](#PS-NULL) | Un estilo de línea que es invisible. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | Un estilo de línea que es de color sólido. |
| [PS_USERSTYLE](#PS-USERSTYLE) | Un estilo de línea que se define mediante una matriz de estilo, que especifica las longitudes de los guiones y los espacios en la línea |
| [PS_ALTERNATE](#PS-ALTERNATE) | Un estilo de línea en el que se establece cada otro píxel. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | Una terminación de línea que especifica extremos cuadrados. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | Una terminación de línea que especifica extremos planos. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | Una unión de línea que especifica uniones biseladas. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | Una unión de línea que especifica uniones en inglete cuando las longitudes de las uniones están dentro del límite de longitud de inglete actual que se establece en el contexto del dispositivo de reproducción. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | Un tipo de pluma que especifica una línea con un ancho medido en unidades lógicas y un estilo que puede contener cualquiera de los atributos de un pincel. |
| [StyleMask](#StyleMask) | La máscara de estilo |
| [EndCapMask](#EndCapMask) | La máscara de terminación |
| [JoinMask](#JoinMask) | La máscara de unión |
| [TypeMask](#TypeMask) | La máscara de tipo |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


Un tipo de lápiz que especifica una línea con un ancho de una unidad lógica y un estilo que es un color sólido.

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


Una terminación de línea que especifica extremos redondos.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


Una unión de línea que especifica uniones redondas.

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


Un estilo de línea que es un color sólido.

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


Un estilo de línea que es discontinuo.

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


Un estilo de línea que es punteado.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


Un estilo de línea que consiste en guiones y puntos alternados.

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


Un estilo de línea que consiste en guiones y puntos dobles.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


Un estilo de línea que es invisible.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


Un estilo de línea que es de color sólido. Cuando este estilo se especifica en un registro de dibujo que toma un rectángulo delimitador, las dimensiones de la figura se reducen para que quepan completamente dentro del rectángulo delimitador, teniendo en cuenta el ancho de la pluma.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


Un estilo de línea que se define mediante una matriz de estilo, que especifica las longitudes de los guiones y los espacios en la línea

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


Un estilo de línea en el que se establece cada otro píxel. Este estilo es aplicable solo a un tipo de pluma de PS\_COSMETIC

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


Una terminación de línea que especifica extremos cuadrados.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


Una terminación de línea que especifica extremos planos.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


Una unión de línea que especifica uniones biseladas.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


Una unión de línea que especifica uniones en inglete cuando las longitudes de las uniones están dentro del límite de longitud de inglete actual que se establece en el contexto del dispositivo de reproducción. Si las longitudes de las uniones superan el límite de inglete, se especifican uniones biseladas

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


Un tipo de pluma que especifica una línea con un ancho medido en unidades lógicas y un estilo que puede contener cualquiera de los atributos de un pincel.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


La máscara de estilo

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


La máscara de terminación

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


La máscara de unión

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


La máscara de tipo

