---
title: "Os22XBitmapHeader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Ein OS/2 2.x OS22XBITMAPHEADER, auch bekannt als BITMAPCOREHEADER2."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

Ein OS/2 2.x OS22XBITMAPHEADER, auch bekannt als BITMAPCOREHEADER2.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUnits()](#getUnits--) | Gibt die Einheiten zurück. |
| [getReserved()](#getReserved--) | Gibt das Reservierte zurück. |
| [getRecording()](#getRecording--) | Gibt die Aufnahme zurück. |
| [getRendering()](#getRendering--) | Gibt das Rendering zurück. |
| [getSize1()](#getSize1--) | Gibt die Größe1 zurück. |
| [getSize2()](#getSize2--) | Gibt die Größe2 zurück. |
| [getColorEncoding()](#getColorEncoding--) | Gibt die Farbcodierung zurück. |
| [getIdentifier()](#getIdentifier--) | Gibt den Bezeichner zurück. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


Gibt die Einheiten zurück.

**Returns:**
int - Typ der zur Messung der Auflösung verwendeten Einheiten
### getReserved() {#getReserved--}
```
public int getReserved()
```


Gibt das Reservierte zurück.

**Returns:**
int - Struktur auffüllen auf 4-Byte-Grenze
### getRecording() {#getRecording--}
```
public int getRecording()
```


Gibt die Aufnahme zurück.

**Returns:**
int - Aufzeichnungsalgorithmus
### getRendering() {#getRendering--}
```
public int getRendering()
```


Gibt das Rendering zurück.

**Returns:**
int - Verwendeter Halbtonalgorithmus
### getSize1() {#getSize1--}
```
public int getSize1()
```


Gibt die Größe1 zurück.

**Returns:**
int - Reserviert für die Verwendung des Halbtonalgorithmus
### getSize2() {#getSize2--}
```
public int getSize2()
```


Gibt die Größe2 zurück.

**Returns:**
int - Reserviert für die Verwendung des Halbtonalgorithmus
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


Gibt die Farbcodierung zurück.

**Returns:**
int - Im Bitmap verwendetes Farbmodell
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Gibt den Bezeichner zurück.

**Returns:**
int - Für die Anwendung reserviert
