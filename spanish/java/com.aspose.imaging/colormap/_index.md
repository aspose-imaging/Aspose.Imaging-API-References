---
title: "ColorMap"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define un mapa para convertir colores."
type: docs
weight: 25
url: /es/java/com.aspose.imaging/colormap/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMap
```

Define un mapa para convertir colores. Varios métodos de la clase [ImageAttributes](../../com.aspose.imaging/imageattributes) ajustan los colores de la imagen usando una tabla de remapeo de colores, que es una matriz de estructuras `com.aspose.imaging.ColorMap`. No heredable.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorMap()](#ColorMap--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getOldColor()](#getOldColor--) | Obtiene la estructura `com.aspose.imaging.Color` existente que se convertirá. |
| [setOldColor(Color value)](#setOldColor-com.aspose.imaging.Color-) | Establece la estructura `com.aspose.imaging.Color` existente que se convertirá. |
| [getNewColor()](#getNewColor--) | Obtiene la nueva estructura `com.aspose.imaging.Color` a la que convertir. |
| [setNewColor(Color value)](#setNewColor-com.aspose.imaging.Color-) | Establece la nueva estructura `com.aspose.imaging.Color` a la que convertir. |
### ColorMap() {#ColorMap--}
```
public ColorMap()
```


### getOldColor() {#getOldColor--}
```
public Color getOldColor()
```


Obtiene la estructura `com.aspose.imaging.Color` existente que se convertirá.

**Returns:**
[Color](../../com.aspose.imaging/color) - The existing `com.aspose.imaging.Color` structure to be converted.
### setOldColor(Color value) {#setOldColor-com.aspose.imaging.Color-}
```
public void setOldColor(Color value)
```


Establece la estructura `com.aspose.imaging.Color` existente que se convertirá.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | La estructura `com.aspose.imaging.Color` existente que se convertirá. |

### getNewColor() {#getNewColor--}
```
public Color getNewColor()
```


Obtiene la nueva estructura `com.aspose.imaging.Color` a la que convertir.

**Returns:**
[Color](../../com.aspose.imaging/color) - The new `com.aspose.imaging.Color` structure to which to convert.
### setNewColor(Color value) {#setNewColor-com.aspose.imaging.Color-}
```
public void setNewColor(Color value)
```


Establece la nueva estructura `com.aspose.imaging.Color` a la que convertir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | La nueva estructura `com.aspose.imaging.Color` a la que convertir. |

