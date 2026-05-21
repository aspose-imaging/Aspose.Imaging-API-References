---
title: "PdfCoreOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "De vanliga alternativen för konvertering till PDF"
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.pdf/pdfcoreoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

De vanliga alternativen för konvertering till PDF
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Anger hur många nivåer av innehållsförteckningsobjekt som ska inkluderas i dokumentets innehållsförteckning. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Anger hur många nivåer av innehållsförteckningsobjekt som ska inkluderas i dokumentets innehållsförteckning. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Anger hur många nivåer i dokumentets innehållsförteckning som ska visas expanderade när PDF-filen visas. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Anger hur många nivåer i dokumentets innehållsförteckning som ska visas expanderade när PDF-filen visas. |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Anger på vilken nivå i dokumentets innehållsförteckning bokmärkesobjekt ska visas. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Anger på vilken nivå i dokumentets innehållsförteckning bokmärkesobjekt ska visas. |
| [getJpegQuality()](#getJpegQuality--) | Anger kvaliteten på JPEG-komprimering för bilder (om JPEG-komprimering används). |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Anger kvaliteten på JPEG-komprimering för bilder (om JPEG-komprimering används). |
| [getPdfCompliance()](#getPdfCompliance--) | Hämtar PDF-kompatibiliteten. |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | Ställer in PDF-kompatibiliteten. |
| [getCompression()](#getCompression--) | Hämtar komprimeringen. |
| [setCompression(int value)](#setCompression-int-) | Anger komprimeringen. |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Anger hur många nivåer av innehållsförteckningsobjekt som ska inkluderas i dokumentets innehållsförteckning. 0 - ingen innehållsförteckning, 1 - en nivå och så vidare. Standard är 0.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Anger hur många nivåer av innehållsförteckningsobjekt som ska inkluderas i dokumentets innehållsförteckning. 0 - ingen innehållsförteckning, 1 - en nivå och så vidare. Standard är 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


Anger hur många nivåer i dokumentets innehållsförteckning som ska visas expanderade när PDF-filen visas. 0 - dokumentets innehållsförteckning är inte expanderad. 1 - objekt på första nivån är expanderade och så vidare. Standard är 0.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


Anger hur många nivåer i dokumentets innehållsförteckning som ska visas expanderade när PDF-filen visas. 0 - dokumentets innehållsförteckning är inte expanderad. 1 - objekt på första nivån är expanderade och så vidare. Standard är 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Anger på vilken nivå i dokumentets innehållsförteckning bokmärkesobjekt ska visas. 0 - visas inte. 1 på första nivån och så vidare. Standard är 0.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Anger på vilken nivå i dokumentets innehållsförteckning bokmärkesobjekt ska visas. 0 - visas inte. 1 på första nivån och så vidare. Standard är 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Anger kvaliteten på JPEG-komprimering för bilder (om JPEG-komprimering används). Standard är 95.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Anger kvaliteten på JPEG-komprimering för bilder (om JPEG-komprimering används). Standard är 95.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


Hämtar PDF-kompatibiliteten.

**Returns:**
int - PDF-kompatibiliteten.
### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


Ställer in PDF-kompatibiliteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | PDF-kompatibiliteten. |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Hämtar komprimeringen.

Värde: Kompressionen.

**Returns:**
int - komprimeringen.
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Anger komprimeringen.

Värde: Kompressionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | kompressionen. |

