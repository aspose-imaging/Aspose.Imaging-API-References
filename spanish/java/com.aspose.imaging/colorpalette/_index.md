---
title: "ColorPalette"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define una matriz de colores que forman una paleta de colores."
type: docs
weight: 28
url: /es/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Define una matriz de colores que forman una paleta de colores. Los colores son colores ARGB de 32 bits. No heredable.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Inicializa una nueva instancia de la clase `ColorPalette`. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Inicializa una nueva instancia de la clase `ColorPalette` y IsCompactPalette es false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | Inicializa una nueva instancia de la clase `ColorPalette`. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | Inicializa una nueva instancia de la clase `ColorPalette` y IsCompactPalette es false. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Obtiene el recuento de entradas. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtiene una matriz de estructuras ARGB de 32 bits. |
| [getEntries()](#getEntries--) | Obtiene una matriz de estructuras `com.aspose.imaging.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Obtiene o establece un valor que indica si se utiliza una paleta compacta. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | Copia la paleta. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | Copia la paleta. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Obtiene el índice del color más cercano. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | Obtiene el índice del color más cercano. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [getColor(int index)](#getColor-int-) | Obtiene el color de la paleta por índice. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Inicializa una nueva instancia de la clase `ColorPalette`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb32Entries | int[] | Las entradas de la paleta de colores ARGB de 32 bits. |
| isCompactPalette | boolean | Indica si la paleta es compacta. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Inicializa una nueva instancia de la clase `ColorPalette` y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb32Entries | int[] | Las entradas de la paleta de colores ARGB de 32 bits. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Inicializa una nueva instancia de la clase `ColorPalette`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Las entradas de la paleta de colores. |
| isCompactPalette | boolean | Indica si la paleta es compacta. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


Inicializa una nueva instancia de la clase `ColorPalette` y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Las entradas de la paleta de colores. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Obtiene el recuento de entradas.

**Returns:**
int - El recuento de entradas.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Obtiene una matriz de estructuras ARGB de 32 bits.

**Returns:**
int[] - Las entradas. La copia del arreglo de los valores ARGB de 32 bits que componen este [ColorPalette](../../com.aspose.imaging/colorpalette).
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Obtiene una matriz de estructuras `com.aspose.imaging.Color`.

**Returns:**
com.aspose.imaging.Color[] - Las entradas. La copia del arreglo de las estructuras [Color](../../com.aspose.imaging/color) que componen este [ColorPalette](../../com.aspose.imaging/colorpalette).
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Obtiene o establece un valor que indica si se utiliza una paleta compacta.

**Returns:**
boolean - `true` si se usa una paleta compacta; de lo contrario, `false`.

Una paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible, o en otras palabras, la imagen será más compacta y ocupará menos espacio; de lo contrario habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las posibles entradas de paleta. Establecer este valor en `true` y cambiar las entradas de la paleta puede causar una penalización de rendimiento ya que puede producirse movimiento de datos, así que úselo con cuidado.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copia la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores. |
| useCompactPalette | boolean | Indica si la paleta es compacta. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Copia la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


Obtiene el índice del color más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb32Color | int | El color ARGB de 32 bits. |

**Returns:**
int - El índice del color más cercano.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


Obtiene el índice del color más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | El color. |

**Returns:**
int - El índice del color más cercano.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Obtiene el color de la paleta ARGB de 32 bits por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de color de la paleta ARGB de 32 bits. |

**Returns:**
int - La entrada de la paleta de colores especificada por el `index`.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Obtiene el color de la paleta por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de color de la paleta. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color palette entry specified by the `index`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
