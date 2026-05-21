---
title: "BigTiffOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para la creación del formato de imagen raster BigTIFF está diseñada específicamente para atender los requisitos únicos de aplicaciones que utilizan datos de imagen a gran escala provenientes de escáneres."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

La API para la creación del formato de imagen raster BigTIFF está diseñada específicamente para atender los requisitos únicos de aplicaciones que utilizan datos de imágenes a gran escala provenientes de escáneres. Esta API facilita la generación sin problemas del formato BigTIFF, que combina múltiples imágenes TIFF en una única imagen completa. Garantiza un procesamiento eficiente de datos de imagen extensos, proporcionando a los desarrolladores una herramienta poderosa para crear y manipular formatos de alta resolución y multi‑imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | Inicializa una nueva instancia de la clase [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Inicializa una nueva instancia de la clase [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la clase [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | Inicializa una nueva instancia de la clase [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Clona esta instancia. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


Inicializa una nueva instancia de la clase [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). Por defecto se utiliza la convención little endian.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expectedFormat | int | El formato de archivo Tiff esperado. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


Inicializa una nueva instancia de la clase [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | La fuente de opciones. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


Inicializa una nueva instancia de la clase [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas para la inicialización de opciones. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


Inicializa una nueva instancia de la clase [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expectedFormat | int | El formato de archivo Tiff esperado. |
| byteOrder | int | El orden de bytes del formato de archivo tiff a usar. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clona esta instancia.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
