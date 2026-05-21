---
title: "BigTiffOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API de création du format d'image raster BigTIFF est spécifiquement conçue pour répondre aux exigences uniques des applications utilisant des données d'imagerie à grande échelle provenant de scanners."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

L'API de création du format d'image raster BigTIFF est spécialement conçue pour répondre aux exigences uniques des applications utilisant des données d'imagerie à grande échelle provenant de scanners. Cette API facilite la génération transparente du format BigTIFF, qui combine plusieurs images TIFF en une seule image complète. Elle assure un traitement efficace de volumes importants de données d'image, offrant aux développeurs un outil puissant pour créer et manipuler des formats haute résolution et multi‑images.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | Initialise une nouvelle instance de la classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Initialise une nouvelle instance de la classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | Initialise une nouvelle instance de la classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clone cette instance. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


Initialise une nouvelle instance de la classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). Par défaut, la convention little endian est utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| expectedFormat | int | Le format de fichier Tiff attendu. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


Initialise une nouvelle instance de la classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | La source des options. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


Initialise une nouvelle instance de la classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les balises pour l'initialisation des options. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


Initialise une nouvelle instance de la classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| expectedFormat | int | Le format de fichier Tiff attendu. |
| byteOrder | int | L'ordre des octets du format de fichier tiff à utiliser. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clone cette instance.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
