---
title: "DataStreamSupporter"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El contenedor del flujo de datos."
type: docs
weight: 39
url: /es/java/com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

El contenedor del flujo de datos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtiene el flujo de datos del objeto. |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos. |
| [cacheData()](#cacheData--) | Cachea los datos y asegura que no se realizará una carga adicional de datos desde el `DataStreamSupporter.DataStreamContainer` subyacente. |
| [save()](#save--) | Guarda los datos del objeto en el `DataStreamSupporter` actual. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Guarda los datos del objeto en el flujo especificado. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Guarda los datos del objeto en el flujo especificado. |
| [save(String filePath)](#save-java.lang.String-) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Guarda los datos del objeto en la ubicación de archivo especificada. |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Obtiene el flujo de datos del objeto.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos.

**Returns:**
boolean - un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos.
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Cachea los datos y asegura que no se realizará una carga adicional de datos desde el `DataStreamSupporter.DataStreamContainer` subyacente.


**Example: The following example shows how image caching affects performance.**
El siguiente ejemplo muestra cómo el almacenamiento en caché de imágenes afecta el rendimiento. En general, leer datos en caché se realiza más rápido que leer datos no almacenados en caché.
``` java
String dir = "c:\\temp\\";

// Carga una imagen desde un archivo PNG.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Almacena en caché todos los datos de píxeles para que no se realice una carga adicional de datos desde el flujo de datos subyacente
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Leer todos los píxeles es bastante rápido.
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

// Cargar una imagen desde un archivo PNG
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Leer todos los píxeles no es tan rápido como al almacenar en caché
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

// La salida puede verse así:
//Leer todos los píxeles en caché tomó 2954 ms.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//en com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:58)
```

### save() {#save--}
```
public void save()
```


Guarda los datos del objeto en el `DataStreamSupporter` actual.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Guarda los datos del objeto en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | El flujo donde guardar los datos del objeto. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Guarda los datos del objeto en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El flujo donde guardar los datos del objeto. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del objeto. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del objeto. |
| overWrite | boolean | si se establece en `true` sobrescribe el contenido del archivo, de lo contrario se producirá una adición. |

