---
title: "FeatheringSettings"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Una clase de configuración de difuminado."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

Una clase de configuración de difuminado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | Inicializa una nueva instancia de la clase [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSize()](#getSize--) | Obtiene el tamaño del difuminado. |
| [setSize(int value)](#setSize-int-) | Establece el tamaño del difuminado. |
| [getMode()](#getMode--) | Obtiene el modo del algoritmo de difuminado. |
| [setMode(int value)](#setMode-int-) | Establece el modo del algoritmo de difuminado. |

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

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


Inicializa una nueva instancia de la clase [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

### getSize() {#getSize--}
```
public final int getSize()
```


Obtiene el tamaño del difuminado.

Valor: El tamaño del pincel de difuminado en píxeles.

**Returns:**
int - el tamaño del difuminado.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Establece el tamaño del difuminado.

Valor: El tamaño del pincel de difuminado en píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el tamaño del difuminado. |

### getMode() {#getMode--}
```
public final int getMode()
```


Obtiene el modo del algoritmo de difuminado.

Valor: El modo del algoritmo de difuminado.

**Returns:**
int - el modo del algoritmo de difuminado.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Establece el modo del algoritmo de difuminado.

Valor: El modo del algoritmo de difuminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el modo del algoritmo de difuminado. |

