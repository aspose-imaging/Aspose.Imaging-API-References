---
title: "BigTiffOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:t för BigTIFF rasterbildformatsskapande är specifikt utformat för att tillgodose de unika kraven hos applikationer som använder storskalig bilddata från skannrar."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

API‑et för skapande av rasterbildformatet BigTIFF är specifikt utformat för att tillgodose de unika kraven hos applikationer som använder storskalig bilddata från skannrar. Detta API underlättar sömlös generering av BigTIFF‑formatet, som kombinerar flera TIFF‑bilder till en enda omfattande bild. Det säkerställer effektiv bearbetning av omfattande bilddata och ger utvecklare ett kraftfullt verktyg för att skapa och manipulera högupplösta, multi‑bildformat.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | Initierar en ny instans av klassen [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Initierar en ny instans av klassen [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | Initierar en ny instans av klassen [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Klonar den här instansen. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


Initierar en ny instans av klassen [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). Som standard används little‑endian‑konventionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expectedFormat | int | Det förväntade Tiff‑filformatet. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


Initierar en ny instans av klassen [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Källan för alternativen. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


Initierar en ny instans av klassen [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Taggarna för initiering av alternativ. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


Initierar en ny instans av klassen [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expectedFormat | int | Det förväntade Tiff‑filformatet. |
| byteOrder | int | Byteordningen för tiff‑filformatet som ska användas. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Klonar den här instansen.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
