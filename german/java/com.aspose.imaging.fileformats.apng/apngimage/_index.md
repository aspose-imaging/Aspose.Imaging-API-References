---
title: "ApngImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für das Bilddateiformat Animated PNG Animated Portable Network Graphics ist eine vielseitige Lösung für Entwickler, die animierte Inhalte in ihre Anwendungen integrieren möchten."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Die API für das Bilddateiformat Animated PNG (Animated Portable Network Graphics) ist eine vielseitige Lösung für Entwickler, die animierte Inhalte in ihre Anwendungen integrieren möchten. Diese API bietet umfangreiche Kontrolle über Frame‑Einstellungen und ermöglicht es den Benutzern, frame‑spezifische Parameter festzulegen, einschließlich Schleifendauer und PNG‑Dateieinstellungen. Mit diesem funktionsreichen Werkzeug können Sie die Anzeige von APNG‑Bildern mühelos verwalten und optimieren, Bilder importieren und exportieren und so die dynamischen und interaktiven Aspekte Ihrer Anwendungen verbessern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Beginnen Sie mit der Arbeit an der Klasse [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage), indem Sie mühelos eine neue Instanz initialisieren. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Greifen Sie schnell auf Informationen zum Dateiformat zu mit dieser praktischen Eigenschaft. |
| [getPageCount()](#getPageCount--) | Ermitteln Sie die Gesamtzahl der Seiten in Ihrer Bilddatei mühelos mit dieser Eigenschaft. |
| [getPages()](#getPages--) | Greifen Sie mühelos auf die Seiten Ihres Bildes zu mit dieser praktischen Eigenschaft. |
| [getNumPlays()](#getNumPlays--) | Steuern Sie mühelos die Anzahl der Wiederholungen Ihrer Animation mit dieser vielseitigen Eigenschaft. |
| [setNumPlays(int value)](#setNumPlays-int-) | Steuern Sie mühelos die Anzahl der Wiederholungen Ihrer Animation mit dieser vielseitigen Eigenschaft. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Passen Sie einfach die Standard‑Frame‑Dauer für das Erstellen neuer Frames mit dieser flexiblen Eigenschaft an. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Passen Sie einfach die Standard‑Frame‑Dauer für das Erstellen neuer Frames mit dieser flexiblen Eigenschaft an. |
| [getInterlaced()](#getInterlaced--) | Bestimmen Sie schnell, ob dieses [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)-Objekt interlaced ist, mit dieser praktischen Eigenschaft. |
| [getOriginalOptions()](#getOriginalOptions--) | Rufen Sie Optionen basierend auf den ursprünglichen Dateieinstellungen mühelos mit dieser intuitiven Methode ab. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Rufen Sie die Standardoptionen mühelos mit dieser einfachen Methode ab. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Erhalten Sie schnell Datum und Uhrzeit, wann das Ressourcenbild zuletzt geändert wurde, mit dieser benutzerfreundlichen Methode. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Fügen Sie dem Bild mühelos eine neue Seite hinzu mit dieser intuitiven Methode. |
| [addFrame()](#addFrame--) | /\\*\\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Erweitern Sie Ihre Frame‑Sammlung mühelos, indem Sie am Ende einen neuen Frame hinzufügen, mit dieser intuitiven Methode. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Erweitern Sie Ihre Frame‑Sammlung nahtlos, indem Sie einen neuen Frame an das mit dieser intuitiven Methode anhängen. |
| [insertFrame(int index)](#insertFrame-int-) | Fügen Sie mühelos einen neuen Frame in Ihre Frame‑Sammlung an der angegebenen Stelle mit dieser intuitiven Methode ein. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Fügt einen neuen Frame in die eigene Frame‑Sammlung an dem angegebenen Index ein. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Fügt einen neuen Frame in die eigene Frame‑Sammlung an dem angegebenen Index ein. |
| [popFrameAt(int index)](#popFrameAt-int-) | Entfernen und holen Sie den Frame am angegebenen Index aus Ihrer Frame‑Sammlung mit dieser intuitiven Methode. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Entfernen Sie den Frame am angegebenen Index aus Ihrer Frame‑Sammlung nahtlos mit dieser Methode. |
| [removeAllFrames()](#removeAllFrames--) | Leeren Sie Ihre Frame‑Sammlung, indem Sie alle Frames entfernen, mit dieser intuitiven Methode. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Legen Sie das angegebene Rasterbild als Standardbild für die aktuelle Animation fest, mühelos mit dieser Methode. |
| [resetDefaultImage()](#resetDefaultImage--) | Entfernen Sie ein zuvor festgelegtes Standardbild mit dieser intuitiven Methode. |

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

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


Beginnen Sie mit der Arbeit an der Klasse [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage), indem Sie mühelos eine neue Instanz initialisieren. Perfekt für Entwickler, die ApngImage‑Objekte schnell und effizient in ihren Projekten einsetzen möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Die Optionen. |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Greifen Sie schnell auf Informationen zum Dateiformat über diese praktische Eigenschaft zu. Ideal für Entwickler, die Details zum Format ihrer Apng‑Dateien leicht abrufen müssen.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Ermitteln Sie mühelos die Gesamtzahl der Seiten in Ihrer Bilddatei über diese Eigenschaft. Ideal für Entwickler, die schnellen Zugriff auf Seitenzählungsinformationen benötigen.

Wert: Die Seitenanzahl.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


Greifen Sie mühelos über diese praktische Eigenschaft auf die Seiten Ihres Bildes zu. Perfekt für Entwickler, die schnellen und einfachen Zugriff auf einzelne Seiten zur Manipulation suchen.

Wert: Die Seiten.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Steuern Sie mühelos die Anzahl der Wiederholungen Ihrer Animation mit dieser vielseitigen Eigenschaft. Perfekt für Entwickler, die eine präzise Kontrolle über das Animationsverhalten benötigen, mit Unterstützung für unendliche Schleifen, wenn der Wert 0 ist.

Wert: Die Anzahl der Wiederholungen.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Steuern Sie mühelos die Anzahl der Wiederholungen Ihrer Animation mit dieser vielseitigen Eigenschaft. Perfekt für Entwickler, die eine präzise Kontrolle über das Animationsverhalten benötigen, mit Unterstützung für unendliche Schleifen, wenn der Wert 0 ist.

Wert: Die Anzahl der Wiederholungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Passen Sie die Standarddauer einzelner Frames für die Erstellung neuer Frames mit dieser flexiblen Eigenschaft einfach an. Perfekt für Entwickler, die die Frame‑Zeitsteuerung in ihren Animationen effizient anpassen möchten.

Wert: Die Standard-Frame‑Dauer in Millisekunden.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Passen Sie die Standarddauer einzelner Frames für die Erstellung neuer Frames mit dieser flexiblen Eigenschaft einfach an. Perfekt für Entwickler, die die Frame‑Zeitsteuerung in ihren Animationen effizient anpassen möchten.

Wert: Die Standard-Frame‑Dauer in Millisekunden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Bestimmen Sie schnell, ob dieses [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)-Objekt mit dieser praktischen Eigenschaft interlaced ist. Ideal für Entwickler, die den Interlacing‑Status von PNG‑Bildern leicht prüfen müssen.

Wert: `true`, wenn interlaced; andernfalls `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Rufen Sie Optionen basierend auf den ursprünglichen Dateieinstellungen mühelos mit dieser intuitiven Methode ab. Perfekt für Entwickler, die Einstellungen nutzen möchten, die den Merkmalen der Originaldatei entsprechen. Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der Methode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG‑Bild mit 1‑Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie an die Methode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) als zweiten Parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Rufen Sie die Standardoptionen mühelos mit dieser einfachen Methode ab. Ideal für Entwickler, die schnellen Zugriff auf die Standard‑Apng‑Bildeinstellungen benötigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | java.lang.Object[] | Die Argumente. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Ermitteln Sie schnell das Datum und die Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde, mit dieser benutzerfreundlichen Methode. Ideal für Entwickler, die Änderungen nachverfolgen und Ressourcen effektiv verwalten müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| useDefault | boolean | Wenn auf `true` gesetzt, verwendet es die Informationen aus FileInfo als Standardwert. |

**Returns:**
java.util.Date - Das Datum und die Uhrzeit, zu der das Ressourcenbild zuletzt geändert wurde.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Fügen Sie dem Bild mühelos eine neue Seite mit dieser intuitiven Methode hinzu. Perfekt für Entwickler, die den Inhalt ihrer Bilddateien dynamisch erweitern möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Die hinzuzufügende Seite. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\\*\\*

Fügen Sie Ihrer Frame‑Sammlung einfach ein neues Frame am Ende mit dieser einfachen Methode hinzu. Ideal für Entwickler, die ihre Frame‑Sammlung für Animationen mit Mehrfach‑Frame‑Bildern dynamisch erweitern möchten. Ein neues Frame wird basierend auf der Größe des aktuellen Bildes erstellt.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Erweitern Sie Ihre Frame‑Sammlung mühelos, indem Sie mit dieser intuitiven Methode ein neues Frame am Ende hinzufügen. Perfekt für Entwickler, die ihre Animationen von Mehrfach‑Frame‑Bildern dynamisch verbessern möchten. Der Inhalt des neuen Frames wird aus dem angegebenen Bild übernommen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Frame‑Bild. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Erweitern Sie Ihre Frame‑Sammlung nahtlos, indem Sie mit dieser intuitiven Methode ein neues Frame anhängen. Ideal für Entwickler, die ihre Animationen von Mehrfach‑Frame‑Bildern bereichern möchten. Der Inhalt des neuen Frames wird aus dem angegebenen Bild übernommen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Frame‑Bild. |
| frameTime | long | Die Frame‑Dauer in Millisekunden. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Fügen Sie mühelos ein neues Frame an der angegebenen Position in Ihre Frame‑Sammlung ein mit dieser intuitiven Methode. Ideal für Entwickler, die eine präzise Kontrolle über die Anordnung der Frames in ihren Animationen von Mehrfach‑Frame‑Bildern benötigen. Ein neues Frame wird basierend auf der Größe des aktuellen Bildes erstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


Fügt ein neues Frame in die eigene Frame‑Sammlung an dem angegebenen Index ein. Der Inhalt des neuen Frames wird aus dem angegebenen Bild übernommen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Frame‑Bild. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


Fügt ein neues Frame in die eigene Frame‑Sammlung an dem angegebenen Index ein. Der Inhalt des neuen Frames wird aus dem angegebenen Bild übernommen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Frame‑Bild. |
| frameTime | long | Die Frame‑Dauer in Millisekunden. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


Entfernen und holen Sie das Frame am angegebenen Index aus Ihrer Frame‑Sammlung mit dieser intuitiven Methode. Perfekt für Entwickler, die eine effiziente Verwaltung von Frames in ihren Animationen anstreben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


Entfernen Sie das Frame am angegebenen Index aus Ihrer Frame‑Sammlung nahtlos mit dieser Methode. Perfekt für Entwickler, die eine optimierte Verwaltung von Frames in ihren Mehrfach‑Frame‑Bildern wünschen. Das zu löschende Frame wird freigegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Leeren Sie Ihre Frame-Sammlung, indem Sie alle Frames mit dieser intuitiven Methode entfernen. Ideal für Entwickler, die ihre Animationen zurücksetzen oder aktualisieren möchten.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Legen Sie das angegebene Rasterbild mühelos mit dieser Methode als Standardbild für die aktuelle Animation fest. Perfekt für Entwickler, die das Standardbild in ihren Animationen anpassen möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Entfernen Sie ein zuvor festgelegtes Standardbild mit dieser intuitiven Methode. Ideal für Entwickler, die das Standardbild in ihrer Animation zurücksetzen oder löschen möchten. Danach ist das Standardbild der erste Frame in der eigenen Frame-Sammlung (es kann mit dieser Methode nicht gelöscht werden).

