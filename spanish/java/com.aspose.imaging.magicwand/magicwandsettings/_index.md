---
title: "MagicWandSettings"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Una clase de configuración de selección de Magic Wand."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

Una clase de configuración de selección de Magic Wand.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | Inicializa una nueva instancia de la clase [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | Inicializa una nueva instancia de la clase [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | Obtiene los límites del área para el trabajo del algoritmo. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | Establece los límites del área para el trabajo del algoritmo. |
| [getPoint()](#getPoint--) | Obtiene el punto de referencia para el trabajo del algoritmo. |
| [getThreshold()](#getThreshold--) | Obtiene el nivel de tolerancia para la comparación de color de píxeles. |
| [setThreshold(int value)](#setThreshold-int-) | Establece el nivel de tolerancia para la comparación de color de píxeles. |
| [getContiguousMode()](#getContiguousMode--) | Obtiene un valor que indica si la varita mágica definirá solo píxeles contiguos. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | Establece un valor que indica si la varita mágica definirá solo píxeles contiguos. |
| [getDirectionalMode()](#getDirectionalMode--) | Obtiene el modo del algoritmo de búsqueda de relleno: búsqueda en cuatro u ocho direcciones. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | Establece el modo del algoritmo de búsqueda de relleno: búsqueda en cuatro u ocho direcciones. |
| [getColorCompareMode()](#getColorCompareMode--) | Obtiene el algoritmo que determina cómo se comparan los colores. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | Establece el algoritmo que determina cómo se comparan los colores. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | Obtiene el algoritmo de comparación de color personalizado si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) está configurado a [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | Establece el algoritmo de comparación de color personalizado si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) está configurado a [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nueva máscara usando la herramienta magic wand basada en el tono y color del píxel (120, 100) con un umbral personalizado igual a 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Aplicar máscara a la imagen
            .apply();

    // Guardar imagen con la opción de tipo de color de transparencia forzada
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```


## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nueva máscara usando la herramienta magic wand basada en el tono y color del píxel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Unir la máscara existente con la especificada creada por la herramienta magic wand
            .union(new MagicWandSettings(416, 387))
            // Invertir la máscara existente
            .invert()
            // Restar la máscara especificada creada por la herramienta magic wand con el umbral especificado de la existente
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Restar cuatro máscaras rectangulares especificadas de la máscara existente una por una
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Suavizar la máscara con los ajustes especificados
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Aplicar máscara a la imagen
            .apply();

    // Guardar imagen
    image.save(outputFilePath);
}

```

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


Inicializa una nueva instancia de la clase [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El punto de referencia. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


Inicializa una nueva instancia de la clase [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto de referencia. |
| y | int | La coordenada y del punto de referencia. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


Obtiene los límites del área para el trabajo del algoritmo.

Valor: El rectángulo que representa los límites del área de interés.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


Establece los límites del área para el trabajo del algoritmo.

Valor: El rectángulo que representa los límites del área de interés.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | los límites del área para el trabajo del algoritmo. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


Obtiene el punto de referencia para el trabajo del algoritmo.

Valor: El valor `Point`.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


Obtiene el nivel de tolerancia para la comparación de color de píxeles.

Valor: El umbral para la comparación de colores.

**Returns:**
int - el nivel de tolerancia para la comparación del color de los píxeles.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


Establece el nivel de tolerancia para la comparación de color de píxeles.

Valor: El umbral para la comparación de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el nivel de tolerancia para la comparación del color de los píxeles. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


Obtiene un valor que indica si la varita mágica definirá solo píxeles contiguos.

Valor: `true` si el elemento está habilitado; de lo contrario, `false`. El valor predeterminado es `true`.

**Returns:**
boolean - un valor que indica si la varita mágica definirá solo píxeles contiguos.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


Establece un valor que indica si la varita mágica definirá solo píxeles contiguos.

Valor: `true` si el elemento está habilitado; de lo contrario, `false`. El valor predeterminado es `true`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si la varita mágica definirá solo píxeles contiguos. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


Obtiene el modo del algoritmo de búsqueda de relleno: búsqueda en cuatro u ocho direcciones.

Valor: El modo del algoritmo de búsqueda de relleno.

**Returns:**
int - el modo del algoritmo de búsqueda de relleno: búsqueda en cuatro u ocho direcciones.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


Establece el modo del algoritmo de búsqueda de relleno: búsqueda en cuatro u ocho direcciones.

Valor: El modo del algoritmo de búsqueda de relleno.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el modo del algoritmo de búsqueda de relleno: búsqueda en cuatro u ocho direcciones. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


Obtiene el algoritmo que determina cómo se comparan los colores.

Valor: El modo de comparación de color.

**Returns:**
int - el algoritmo que determina cómo se comparan los colores.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


Establece el algoritmo que determina cómo se comparan los colores.

Valor: El modo de comparación de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el algoritmo que determina cómo se comparan los colores. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


Obtiene el algoritmo de comparación de color personalizado si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) está configurado a [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Valor: El delegado de comparación de color.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


Establece el algoritmo de comparación de color personalizado si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) está configurado a [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Valor: El delegado de comparación de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | el algoritmo de comparación de color personalizado si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) está configurado a [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

