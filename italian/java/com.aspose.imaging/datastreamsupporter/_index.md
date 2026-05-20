---
title: "DataStreamSupporter"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il contenitore del flusso di dati."
type: docs
weight: 39
url: /it/java/com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Il contenitore del flusso di dati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | Restituisce lo stream dei dati dell'oggetto. |
| [isCached()](#isCached--) | Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati. |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati e garantisce che non venga eseguito alcun ulteriore caricamento dei dati dal sottostante `DataStreamSupporter.DataStreamContainer`. |
| [save()](#save--) | Salva i dati dell'oggetto nel corrente `DataStreamSupporter`. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Salva i dati dell'oggetto nello stream specificato. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Salva i dati dell'oggetto nello stream specificato. |
| [save(String filePath)](#save-java.lang.String-) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Salva i dati dell'oggetto nella posizione file specificata. |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Restituisce lo stream dei dati dell'oggetto.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.

**Returns:**
boolean - un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Memorizza nella cache i dati e garantisce che non venga eseguito alcun ulteriore caricamento dei dati dal sottostante `DataStreamSupporter.DataStreamContainer`.


**Example: The following example shows how image caching affects performance.**
Il seguente esempio mostra come la cache delle immagini influisce sulle prestazioni. In generale, la lettura dei dati in cache è più veloce della lettura dei dati non in cache.
``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file PNG.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Memorizza nella cache tutti i dati dei pixel in modo che non venga eseguito alcun ulteriore caricamento dei dati dal flusso di dati sottostante
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // La lettura di tutti i pixel è abbastanza veloce.
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

// Carica un'immagine da un file PNG
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // La lettura di tutti i pixel non è veloce come quando si utilizza la cache
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

// L'output potrebbe apparire così:
//La lettura di tutti i pixel in cache ha impiegato 2954 ms.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//in com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:58)
```

### save() {#save--}
```
public void save()
```


Salva i dati dell'oggetto nel corrente `DataStreamSupporter`.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Salva i dati dell'oggetto nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Lo stream su cui salvare i dati dell'oggetto. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Salva i dati dell'oggetto nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Lo stream su cui salvare i dati dell'oggetto. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file su cui salvare i dati dell'oggetto. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file su cui salvare i dati dell'oggetto. |
| overWrite | boolean | se impostato su `true` sovrascrive il contenuto del file, altrimenti verrà aggiunto. |

