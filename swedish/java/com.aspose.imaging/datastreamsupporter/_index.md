---
title: "DataStreamSupporter"
second_title: "Aspose.Imaging för Java API-referens"
description: "Behållaren för datastream."
type: docs
weight: 39
url: /sv/java/com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Behållaren för datastream.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | Hämtar objektets datastream. |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [cacheData()](#cacheData--) | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande `DataStreamSupporter.DataStreamContainer`. |
| [save()](#save--) | Sparar objektets data till den aktuella `DataStreamSupporter`. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Sparar objektets data till den angivna strömmen. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Sparar objektets data till den angivna strömmen. |
| [save(String filePath)](#save-java.lang.String-) | Sparar objektets data till den angivna filplatsen. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Sparar objektets data till den angivna filplatsen. |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Hämtar objektets datastream.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.

**Returns:**
boolean - ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande `DataStreamSupporter.DataStreamContainer`.


**Example: The following example shows how image caching affects performance.**
Följande exempel visar hur bildcachning påverkar prestanda. I allmänhet utförs läsning av cachad data snabbare än läsning av icke-cachad data.
``` java
String dir = "c:\\temp\\";

// Läs in en bild från en PNG-fil.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Cacha all pixeldata så att ingen ytterligare dataladdning utförs från den underliggande datastreamen
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Att läsa alla pixlar är ganska snabbt.
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

// Läs in en bild från en PNG-fil
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Att läsa alla pixlar är inte lika snabbt som vid cachning
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

// Utdata kan se ut så här:
//Läsning av alla cachade pixlar tog 2954 ms.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//vid com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:58)
```

### save() {#save--}
```
public void save()
```


Sparar objektets data till den aktuella `DataStreamSupporter`.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Sparar objektets data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Strömmen som objektets data ska sparas till. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Sparar objektets data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Strömmen som objektets data ska sparas till. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Sparar objektets data till den angivna filplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för att spara objektets data till. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Sparar objektets data till den angivna filplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för att spara objektets data till. |
| overWrite | boolean | om den är satt till `true` skriv över filens innehåll, annars sker tillägg. |

