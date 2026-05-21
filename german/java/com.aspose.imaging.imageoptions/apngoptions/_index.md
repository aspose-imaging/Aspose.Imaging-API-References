---
title: "ApngOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API zur Erstellung des Bilddateiformats Animated PNG Animated Portable Network Graphics ist ein dynamisches Werkzeug für Entwickler, die fesselnde animierte Bilder erzeugen möchten."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging/imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

Die API zur Erstellung des Bilddateiformats Animated PNG (Animated Portable Network Graphics) ist ein dynamisches Werkzeug für Entwickler, die fesselnde animierte Bilder erzeugen möchten. Mit anpassbaren Optionen wie der Bilddauer und der Anzahl der Wiederholungen ermöglicht diese API die Feinabstimmung animierter Inhalte nach spezifischen Anforderungen. Ob Sie ansprechende Webgrafiken oder interaktive Visualisierungen erstellen, Sie können diese API nutzen, um APNG-Bilder nahtlos einzubinden und dabei die Animationsparameter präzise zu steuern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Initialisiert eine neue Instanz der Klasse [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions). |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | Initialisiert eine neue Instanz der Klasse `ApngOptions`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | Liest die Anzahl der Wiederholungen der Animation. |
| [setNumPlays(int value)](#setNumPlays-int-) | Setzt die Anzahl der Wiederholungen der Animation. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Liest die Standard-Bilddauer. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Setzt die Standard-Bilddauer. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportieren zu APNG-Animation mit unbegrenzten Animationszyklen als Standard
    image.save("Animation1.webp.png", new ApngOptions());
    // Einrichten von Animationszyklen
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
    // Einrichten der Standard-Bilddauer
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


Initialisiert eine neue Instanz der Klasse [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions).

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


Initialisiert eine neue Instanz der Klasse `ApngOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Die PNG-Optionen. |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


Ermittelt die Anzahl der Wiederholungen der Animation. 0 bedeutet unendliche Wiederholung.

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportieren zu APNG-Animation mit unbegrenzten Animationszyklen als Standard
    image.save("Animation1.webp.png", new ApngOptions());
    // Einrichten von Animationszyklen
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


Legt die Anzahl der Wiederholungen der Animation fest. 0 bedeutet unendliche Wiederholung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportieren zu APNG-Animation mit unbegrenzten Animationszyklen als Standard
    image.save("Animation1.webp.png", new ApngOptions());
    // Einrichten von Animationszyklen
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


Liest die Standard-Bilddauer.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


Setzt die Standard-Bilddauer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

