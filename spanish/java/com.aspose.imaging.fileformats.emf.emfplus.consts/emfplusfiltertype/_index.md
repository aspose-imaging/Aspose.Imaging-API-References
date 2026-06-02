---
title: "EmfPlusFilterType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración FilterType define tipos de algoritmos de filtrado que pueden usarse para la mejora de la calidad del texto y los gráficos y el renderizado de imágenes."
type: docs
weight: 22
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

La enumeración FilterType define tipos de algoritmos de filtrado que pueden usarse para la mejora de la calidad del texto y los gráficos y el renderizado de imágenes.
## Campos

| Campo | Descripción |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | Especifica que no se realiza filtrado. |
| [FilterTypePoint](#FilterTypePoint) | Especifica que cada píxel de destino se calcula muestreando el píxel más cercano de la imagen fuente. |
| [FilterTypeLinear](#FilterTypeLinear) | Especifica que se realiza interpolación lineal usando el promedio ponderado de un área de 2x2 píxeles que rodean al píxel fuente. |
| [FilterTypeTriangle](#FilterTypeTriangle) | Especifica que cada píxel de la imagen fuente contribuye por igual a la imagen de destino. |
| [FilterTypeBox](#FilterTypeBox) | Especifica un algoritmo de filtro de caja, en el que cada píxel de destino se calcula promediando un rectángulo de píxeles fuente. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | Especifica que se utiliza un filtro de tienda de 4 muestras. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | Especifica que se utiliza un filtro gaussiano de 4 muestras, lo que crea un efecto de desenfoque en una imagen. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


Especifica que no se realiza filtrado.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


Especifica que cada píxel de destino se calcula muestreando el píxel más cercano de la imagen fuente.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


Especifica que se realiza interpolación lineal usando el promedio ponderado de un área de 2x2 píxeles que rodean al píxel fuente.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


Especifica que cada píxel de la imagen fuente contribuye por igual a la imagen de destino. Este es el algoritmo de filtrado más lento.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


Especifica un algoritmo de filtro de caja, en el que cada píxel de destino se calcula promediando un rectángulo de píxeles de origen. Este algoritmo es útil solo al reducir el tamaño de una imagen.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


Especifica que se utiliza un filtro de tienda de 4 muestras.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


Especifica que se utiliza un filtro gaussiano de 4 muestras, lo que crea un efecto de desenfoque en una imagen.

