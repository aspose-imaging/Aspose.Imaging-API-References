---
title: "WebPOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Crea imágenes web rasterizadas WebP modernas usando nuestra API, que ofrece un soporte robusto para compresión sin pérdida y con pérdida, así como canales alfa y bucles de animación."
type: docs
weight: 53
url: /es/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

Crea imágenes web rasterizadas WebP modernas usando nuestra API, con un soporte robusto para compresión sin pérdida y con pérdida, así como canales alfa y bucles de animación. Mejora tu contenido web con visuales dinámicos mientras optimizas el tamaño de los archivos para mejorar la velocidad de carga y la experiencia del usuario.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLossless()](#getLossless--) | Obtiene o establece un valor que indica si este `WebPOptions` es sin pérdida. |
| [setLossless(boolean value)](#setLossless-boolean-) | Obtiene o establece un valor que indica si este `WebPOptions` es sin pérdida. |
| [getQuality()](#getQuality--) | Obtiene o establece la calidad. |
| [setQuality(float value)](#setQuality-float-) | Obtiene o establece la calidad. |
| [getAnimLoopCount()](#getAnimLoopCount--) | Obtiene o establece el recuento de bucles de animación. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | Obtiene o establece el recuento de bucles de animación. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | Obtiene o establece el color del fondo de la animación. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | Obtiene o establece el color del fondo de la animación. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporta solo las dos primeras páginas. Estas páginas se presentarán como fotogramas animados en el WEBP de salida.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


Obtiene o establece un valor que indica si este `WebPOptions` es sin pérdida.

**Returns:**
booleano - `true` si es sin pérdida; de lo contrario, `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


Obtiene o establece un valor que indica si este `WebPOptions` es sin pérdida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si es sin pérdida; de lo contrario, `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


Obtiene o establece la calidad.

**Returns:**
flotante - La calidad.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


Obtiene o establece la calidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La calidad. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


Obtiene o establece el recuento de bucles de animación.

**Returns:**
entero - El recuento de bucles de animación, 0 - infinito.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


Obtiene o establece el recuento de bucles de animación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El recuento de bucles de animación, 0 - infinito. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


Obtiene o establece el color del fondo de la animación.

**Returns:**
largo - El color del fondo de la animación.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


Obtiene o establece el color del fondo de la animación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | El color del fondo de la animación. |

