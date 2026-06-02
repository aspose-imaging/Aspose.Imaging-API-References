---
title: "DxfOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für die Erstellung von Vektor‑DXF‑Bildern im Drawing Interchange Format bietet maßgeschneiderte Lösungen zur präzisen und flexiblen Erzeugung von AutoCAD‑Zeichnungsdateien."
type: docs
weight: 17
url: /de/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

Die API für die Erstellung von Vektor‑DXF‑Bildern im Drawing Interchange Format (DXF) bietet maßgeschneiderte Lösungen zur präzisen und flexiblen Erzeugung von AutoCAD‑Zeichnungsdateien. Speziell für die Arbeit mit Textzeilen und Bézier‑Kurven entwickelt, können Entwickler diese Elemente effizient manipulieren, Bézier‑Punkte zählen und Kurven in Polylinien umwandeln, um einen nahtlosen Export zu ermöglichen und dabei Kompatibilität und Treue in DXF‑Vektorbildern sicherzustellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | Kopierkonstruktor |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | Wie viele Punkte beim Konvertieren von Bézier-Kurven zu Polylinien erzeugt werden sollen, mindestens 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | Wie viele Punkte beim Konvertieren von Bézier-Kurven zu Polylinien erzeugt werden sollen, mindestens 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | Funktioniert, wenn \#textAsLines auf `true` gesetzt ist. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | Funktioniert, wenn \#textAsLines auf `true` gesetzt ist. |
| [getTextAsLines()](#getTextAsLines--) | Ob Text als Konturen, bestehend aus Polylinien (Standard), oder als editierbare Autocad TEXT-Entitäten exportiert werden soll. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | Ob Text als Konturen, bestehend aus Polylinien (Standard), oder als editierbare Autocad TEXT-Entitäten exportiert werden soll. |

## Example: This example demonstrates export to Dxf format

``` java

//Erstelle eine Image-Instanz und initialisiere sie mit einer vorhandenen Bilddatei vom Speicherort auf der Festplatte.
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


Kopierkonstruktor

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | Die Quelloptionen für das Kopieren |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


Wie viele Punkte beim Konvertieren von Bézier-Kurven zu Polylinien erzeugt werden sollen, mindestens 4. Wird verwendet, wenn (/) und (/) beide /// auf `true` gesetzt sind.

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


Wie viele Punkte beim Konvertieren von Bézier-Kurven zu Polylinien erzeugt werden sollen, mindestens 4. Wird verwendet, wenn (/) und (/) beide /// auf `true` gesetzt sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


Funktioniert, wenn \#textAsLines auf `true` gesetzt ist. Ob Bézier-Kurven in Textkonturen in Mehrpunkt-Polylinien konvertiert werden sollen.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


Funktioniert, wenn \#textAsLines auf `true` gesetzt ist. Ob Bézier-Kurven in Textkonturen in Mehrpunkt-Polylinien konvertiert werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


Ob Text als Konturen, bestehend aus Polylinien (Standard), oder als editierbare Autocad TEXT-Entitäten exportiert werden soll. Wenn diese Option gesetzt ist

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


Ob Text als Konturen, bestehend aus Polylinien (Standard), oder als editierbare Autocad TEXT-Entitäten exportiert werden soll. Wenn diese Option gesetzt ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

