---
title: "BigTiffOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API zur Erstellung des Rasterbildformats BigTIFF ist speziell dafür konzipiert, die einzigartigen Anforderungen von Anwendungen zu erfüllen, die großskalige Bilddaten von Scannern nutzen."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

Die API zur Erstellung des BigTIFF‑Rasterbildformats ist speziell darauf ausgelegt, den einzigartigen Anforderungen von Anwendungen gerecht zu werden, die großskalige Bilddaten von Scannern nutzen. Diese API ermöglicht die nahtlose Erzeugung des BigTIFF‑Formats, das mehrere TIFF‑Bilder zu einem einzigen, umfassenden Bild kombiniert. Sie sorgt für eine effiziente Verarbeitung umfangreicher Bilddaten und bietet Entwicklern ein leistungsstarkes Werkzeug zum Erstellen und Manipulieren hochauflösender Multi‑Bild‑Formate.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | Initialisiert eine neue Instanz der Klasse [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Initialisiert eine neue Instanz der Klasse [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der Klasse [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | Initialisiert eine neue Instanz der Klasse [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Klonen Sie diese Instanz. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


Initialisiert eine neue Instanz der Klasse [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). Standardmäßig wird die Little‑Endian‑Konvention verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expectedFormat | int | Das erwartete Tiff‑Dateiformat. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


Initialisiert eine neue Instanz der Klasse [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Die Optionsquelle. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


Initialisiert eine neue Instanz der Klasse [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die Tags für die Initialisierung der Optionen. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


Initialisiert eine neue Instanz der Klasse [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expectedFormat | int | Das erwartete Tiff‑Dateiformat. |
| byteOrder | int | Die Byte‑Reihenfolge des Tiff‑Dateiformats, die verwendet werden soll. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Klonen Sie diese Instanz.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
