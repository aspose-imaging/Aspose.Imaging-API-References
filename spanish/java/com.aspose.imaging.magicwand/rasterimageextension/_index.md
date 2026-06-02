---
title: "RasterImageExtension"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase con métodos de extensión de máscaras para ."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

Clase con métodos de extensión de máscaras para [RasterImage](../../com.aspose.imaging/rasterimage).
## Métodos

| Método | Descripción |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Crea un [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) con la selección de píxeles con colores similares al color del punto de referencia basado en [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | Aplica [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) al [RasterImage](../../com.aspose.imaging/rasterimage). |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


Crea un [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) con la selección de píxeles con colores similares al color del punto de referencia basado en [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen raster para que el algoritmo funcione. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Los ajustes utilizados para procesar la selección, incluyen el punto de referencia. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


Aplica [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) al [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen a la que aplicar la máscara. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | La máscara a aplicar. |

