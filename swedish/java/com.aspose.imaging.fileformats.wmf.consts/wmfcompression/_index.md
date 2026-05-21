---
title: "WmfCompression"
second_title: "Aspose.Imaging för Java API-referens"
description: "Compression‑enumerationen specificerar komprimeringstypen för en bitmap-bild."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

Compression‑enumerationen specificerar komprimeringstypen för en bitmap-bild.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BI_RGB](#BI-RGB) | Bitmapen är i okomprimerat röd‑grön‑blå (RGB)-format som inte är komprimerat och inte använder färgmasker. |
| [BI_RLE8](#BI-RLE8) | Ett RGB-format som använder run‑length‑kodning (RLE) för komprimering av bitmapar med 8 bitar per pixel. |
| [BI_RLE4](#BI-RLE4) | Ett RGB-format som använder RLE‑komprimering för bitmapar med 4 bitar per pixel. |
| [BI_BITFIELDS](#BI-BITFIELDS) | Bitmap-bilden är inte komprimerad och färgtabellen består av tre DWORD-färgmasker som specificerar de röda, gröna och blå komponenterna, respektive, för varje pixel. |
| [BI_JPEG](#BI-JPEG) | Bilden är en JPEG-bild, enligt specifikationen i [JFIF]. |
| [BI_PNG](#BI-PNG) | Bilden är en PNG-bild, enligt specifikationen i [RFC2083]. |
| [BI_CMYK](#BI-CMYK) | Bilden är i ett okomprimerat CMYK-format. |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | Ett CMYK-format som använder RLE-komprimering för bitmapar med 8 bitar per pixel. |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | Ett CMYK-format som använder RLE-komprimering för bitmapar med 4 bitar per pixel. |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


Bitmapen är i okomprimerat röd‑grön‑blå (RGB)-format som inte är komprimerat och inte använder färgmasker.

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


Ett RGB-format som använder run-length encoding (RLE)-komprimering för bitmapar med 8 bitar per pixel. Komprimeringen använder ett 2‑byteformat bestående av en räknabyte följt av en byte som innehåller ett färgindex.

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


Ett RGB-format som använder RLE-komprimering för bitmapar med 4 bitar per pixel. Komprimeringen använder ett 2‑byteformat bestående av en räknabyte följt av två ordlängds färgindex.

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


Bitmap-bilden är inte komprimerad och färgtabellen består av tre DWORD-färgmasker som specificerar de röda, gröna och blå komponenterna, respektive, för varje pixel. Detta är giltigt när den används med bitmapar på 16 och 32 bitar per pixel.

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


Bilden är en JPEG-bild, enligt specifikationen i [JFIF]. Detta värde SKA endast användas i vissa bitmap‑operationer, såsom JPEG‑pass‑through. Applikationen MÅSTE fråga efter stöd för pass‑through, eftersom inte alla enheter stödjer JPEG‑pass‑through. Att använda icke‑RGB‑bitmapar KAN begränsa metafilens portabilitet till andra enheter. Till exempel stödjer display‑enhetskontexter generellt sett inte detta pass‑through.

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


Bilden är en PNG-bild, enligt specifikationen i [RFC2083]. Detta värde SKA endast användas i vissa bitmap‑operationer, såsom JPEG/PNG‑pass‑through. Applikationen MÅSTE fråga efter stöd för pass‑through, eftersom inte alla enheter stödjer JPEG/PNG‑pass‑through. Att använda icke‑RGB‑bitmapar KAN begränsa metafilens portabilitet till andra enheter. Till exempel stödjer display‑enhetskontexter generellt sett inte detta pass‑through.

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


Bilden är i ett okomprimerat CMYK-format.

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


Ett CMYK-format som använder RLE-komprimering för bitmapar med 8 bitar per pixel. Komprimeringen använder ett 2‑byteformat bestående av en räknabyte följt av en byte som innehåller ett färgindex.

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


Ett CMYK-format som använder RLE-komprimering för bitmapar med 4 bitar per pixel. Komprimeringen använder ett 2‑byteformat bestående av en räknabyte följt av två ordlängds färgindex.

