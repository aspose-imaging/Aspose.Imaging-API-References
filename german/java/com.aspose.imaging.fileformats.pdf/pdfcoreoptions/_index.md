---
title: "PdfCoreOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die gängigen Optionen für die Konvertierung zu PDF"
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.pdf/pdfcoreoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

Die gängigen Optionen für die Konvertierung zu PDF
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Gibt an, wie viele Ebenen von Gliederungselementen in die Dokumentenübersicht aufgenommen werden sollen. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Gibt an, wie viele Ebenen von Gliederungselementen in die Dokumentenübersicht aufgenommen werden sollen. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Gibt an, wie viele Ebenen der Dokumentenübersicht beim Anzeigen der PDF-Datei erweitert angezeigt werden sollen. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Gibt an, wie viele Ebenen der Dokumentenübersicht beim Anzeigen der PDF-Datei erweitert angezeigt werden sollen. |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Gibt an, auf welcher Ebene der Dokumentenübersicht Lesezeichenobjekte angezeigt werden sollen. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Gibt an, auf welcher Ebene der Dokumentenübersicht Lesezeichenobjekte angezeigt werden sollen. |
| [getJpegQuality()](#getJpegQuality--) | Gibt die Qualität der JPEG-Kompression für Bilder an (falls JPEG-Kompression verwendet wird). |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Gibt die Qualität der JPEG-Kompression für Bilder an (falls JPEG-Kompression verwendet wird). |
| [getPdfCompliance()](#getPdfCompliance--) | Liest die PDF-Konformität. |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | Setzt die PDF-Konformität. |
| [getCompression()](#getCompression--) | Liest die Kompression. |
| [setCompression(int value)](#setCompression-int-) | Setzt die Kompression. |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Gibt an, wie viele Ebenen von Gliederungselementen in die Dokumentenübersicht aufgenommen werden sollen. 0 - keine Übersicht, 1 - eine Ebene und so weiter. Standardwert ist 0.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Gibt an, wie viele Ebenen von Gliederungselementen in die Dokumentenübersicht aufgenommen werden sollen. 0 - keine Übersicht, 1 - eine Ebene und so weiter. Standardwert ist 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


Gibt an, wie viele Ebenen der Dokumentenübersicht beim Anzeigen der PDF-Datei erweitert angezeigt werden sollen. 0 - die Dokumentenübersicht ist nicht erweitert. 1 - Elemente der ersten Ebene werden erweitert und so weiter. Standardwert ist 0.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


Gibt an, wie viele Ebenen der Dokumentenübersicht beim Anzeigen der PDF-Datei erweitert angezeigt werden sollen. 0 - die Dokumentenübersicht ist nicht erweitert. 1 - Elemente der ersten Ebene werden erweitert und so weiter. Standardwert ist 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Gibt an, auf welcher Ebene der Dokumentenübersicht Lesezeichenobjekte angezeigt werden sollen. 0 - nicht angezeigt. 1 - auf der ersten Ebene und so weiter. Standardwert ist 0.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Gibt an, auf welcher Ebene der Dokumentenübersicht Lesezeichenobjekte angezeigt werden sollen. 0 - nicht angezeigt. 1 - auf der ersten Ebene und so weiter. Standardwert ist 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Gibt die Qualität der JPEG-Kompression für Bilder an (falls JPEG-Kompression verwendet wird). Standardwert ist 95.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Gibt die Qualität der JPEG-Kompression für Bilder an (falls JPEG-Kompression verwendet wird). Standardwert ist 95.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


Liest die PDF-Konformität.

**Returns:**
int - die PDF-Konformität.
### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


Setzt die PDF-Konformität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die PDF-Konformität. |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Liest die Kompression.

Wert: Die Kompression.

**Returns:**
int - die Kompression.
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Setzt die Kompression.

Wert: Die Kompression.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Kompression. |

