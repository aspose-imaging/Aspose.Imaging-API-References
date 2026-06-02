---
title: "MagicWandTool"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La clase para la lógica principal del algoritmo magic wand."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

La clase para la lógica principal del algoritmo magic wand.
## Métodos

| Método | Descripción |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Crea una nueva [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) basada en [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) y la [RasterImage](../../com.aspose.imaging/rasterimage) de origen. |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Procesa los píxeles cargados. |

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

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


Crea una nueva [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) basada en [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) y la [RasterImage](../../com.aspose.imaging/rasterimage) de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen raster para que el algoritmo funcione. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración del algoritmo magic wand usado al crear la máscara. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Procesa los píxeles cargados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de píxeles. |
| píxeles | int[] | Los píxeles ARGB de 32 bits. |
| start | [Point](../../com.aspose.imaging/point) | El punto de inicio de los píxeles. Si no es igual a (izquierda,arriba) significa que no tenemos un rectángulo completo. |
| end | [Point](../../com.aspose.imaging/point) | El punto final de los píxeles. Si no es igual a (derecha,abajo) significa que no tenemos un rectángulo completo. |

