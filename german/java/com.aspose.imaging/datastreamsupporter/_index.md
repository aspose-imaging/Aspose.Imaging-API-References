---
title: "DataStreamSupporter"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Datenstrom-Container."
type: docs
weight: 39
url: /de/java/com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Der Datenstrom-Container.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | Ruft den Datenstrom des Objekts ab. |
| [isCached()](#isCached--) | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [cacheData()](#cacheData--) | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden `DataStreamSupporter.DataStreamContainer` durchgeführt werden. |
| [save()](#save--) | Speichert die Daten des Objekts im aktuellen `DataStreamSupporter`. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save(String filePath)](#save-java.lang.String-) | Speichert die Daten des Objekts am angegebenen Dateipfad. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Speichert die Daten des Objekts am angegebenen Dateipfad. |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Ruft den Datenstrom des Objekts ab.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.

**Returns:**
boolean – ein Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden `DataStreamSupporter.DataStreamContainer` durchgeführt werden.


**Example: The following example shows how image caching affects performance.**
Das folgende Beispiel zeigt, wie Bild-Caching die Leistung beeinflusst. Im Allgemeinen wird das Lesen zwischengespeicherter Daten schneller ausgeführt als das Lesen nicht zwischengespeicherter Daten.
``` java
String dir = "c:\\temp\\";

// Laden Sie ein Bild aus einer PNG-Datei.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Speichern Sie alle Pixeldaten im Cache, sodass keine zusätzlichen Datenladungen vom zugrunde liegenden Datenstrom durchgeführt werden.
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Das Lesen aller Pixel ist ziemlich schnell.
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = rasterImage.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedTime = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedTime + " ms.");
} finally {
    image.dispose();
}

// Lade ein Bild aus einer PNG-Datei
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Das Lesen aller Pixel ist nicht so schnell wie beim Caching.
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = rasterImage.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedTime = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedTime + " ms.");
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
//Das Lesen aller zwischengespeicherten Pixel dauerte 2954 ms.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//bei com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:58)
```

### save() {#save--}
```
public void save()
```


Speichert die Daten des Objekts im aktuellen `DataStreamSupporter`.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | Der Stream, in dem die Daten des Objekts gespeichert werden. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Der Stream, in dem die Daten des Objekts gespeichert werden. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Speichert die Daten des Objekts am angegebenen Dateipfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Speichert die Daten des Objekts am angegebenen Dateipfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |
| overWrite | boolean | Wenn auf `true` gesetzt, wird der Dateiinhalt überschrieben, andernfalls wird angehängt. |

