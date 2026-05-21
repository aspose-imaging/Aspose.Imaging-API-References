---
title: "ApngOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para la creación del formato de archivo de imagen Animated PNG Animated Portable Network Graphics es una herramienta dinámica para desarrolladores que buscan generar imágenes animadas cautivadoras."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

La API para la creación del formato de archivo de imagen Animated PNG (Animated Portable Network Graphics) es una herramienta dinámica para desarrolladores que buscan generar imágenes animadas cautivadoras. Con opciones personalizables como la duración de fotogramas y el número de repeticiones, esta API permite afinar el contenido animado según necesidades específicas. Ya sea creando gráficos web atractivos o visuales interactivos, puedes aprovechar esta API para incorporar sin problemas imágenes APNG con un control preciso sobre los parámetros de animación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Inicializa una nueva instancia de la clase [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions). |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | Inicializa una nueva instancia de la clase `ApngOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | Obtiene el número de repeticiones de la animación. |
| [setNumPlays(int value)](#setNumPlays-int-) | Establece el número de repeticiones de la animación. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Obtiene la duración predeterminada del fotograma. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Establece la duración predeterminada del fotograma. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportar a animación APNG con ciclos de animación ilimitados por defecto
    image.save("Animation1.webp.png", new ApngOptions());
    // Configuración de ciclos de animación
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Configuración de la duración de fotograma predeterminada
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


Inicializa una nueva instancia de la clase [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions).

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


Inicializa una nueva instancia de la clase `ApngOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Las opciones PNG. |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


Obtiene el número de veces que se repite la animación. 0 indica un bucle infinito.

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportar a animación APNG con ciclos de animación ilimitados por defecto
    image.save("Animation1.webp.png", new ApngOptions());
    // Configuración de ciclos de animación
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


Establece el número de veces que se repite la animación. 0 indica un bucle infinito.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportar a animación APNG con ciclos de animación ilimitados por defecto
    image.save("Animation1.webp.png", new ApngOptions());
    // Configuración de ciclos de animación
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


Obtiene la duración predeterminada del fotograma.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


Establece la duración predeterminada del fotograma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

