---
title: "StreamSource"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une source de flux."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

Représente une source de flux.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | Initialise une nouvelle instance de la classe `StreamSource`. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Initialise une nouvelle instance de la classe `StreamSource`. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | Initialise une nouvelle instance de la classe `StreamSource`. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | Initialise une nouvelle instance de la classe `StreamSource`. |
| [StreamSource()](#StreamSource--) | Initialise une nouvelle instance de la classe `StreamSource` avec un flux Null. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | Initialise une nouvelle instance de la classe `StreamSource`. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | Initialise une nouvelle instance de la classe `StreamSource`. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | Initialise une nouvelle instance de la classe `StreamSource`. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Initialise une nouvelle instance de la classe `StreamSource`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStream()](#getStream--) | Obtient le flux. |
| [getDisposeStream()](#getDisposeStream--) | Obtient une valeur indiquant si le flux doit être libéré chaque fois que le conteneur est libéré. |
| [getStreamContainer()](#getStreamContainer--) | Obtient le conteneur de flux. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//Crée une instance de JpegOptions et définit ses différentes propriétés
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//Crée une instance de System.IO.Stream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// Définit la propriété source pour l'instance de JpegOptions
// Le deuxième paramètre booléen détermine si le flux est libéré une fois sorti de la portée
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// Crée une instance d'Image et appelle la méthode Create avec JpegOptions comme paramètre pour initialiser l'objet Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // Effectuez un traitement d'image
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


Initialise une nouvelle instance de la classe `StreamSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | com.aspose.ms.System.IO.Stream | Le flux à ouvrir. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Initialise une nouvelle instance de la classe `StreamSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à ouvrir. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


Initialise une nouvelle instance de la classe `StreamSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Tableau d'octets qui stocke l'image |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


Initialise une nouvelle instance de la classe `StreamSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | Tampon ByteBuffer pour stocker l'image |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Initialise une nouvelle instance de la classe `StreamSource` avec un flux Null. Ce constructeur permet de créer de nouvelles images sans flux d'entrée, les images étant stockées uniquement en mémoire.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


Initialise une nouvelle instance de la classe `StreamSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier à ouvrir. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


Initialise une nouvelle instance de la classe `StreamSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier à ouvrir. |
| disposeStream | boolean | si défini sur `true`, le flux sera libéré. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


Initialise une nouvelle instance de la classe `StreamSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | com.aspose.ms.System.IO.Stream | Le flux |
| disposeStream | boolean | si défini sur `true`, le flux sera libéré. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Initialise une nouvelle instance de la classe `StreamSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à ouvrir. |
| disposeStream | boolean | si défini sur `true`, le flux sera libéré. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


Obtient le flux.

**Returns:**
com.aspose.ms.System.IO.Stream - Le flux.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


Obtient une valeur indiquant si le flux doit être libéré chaque fois que le conteneur est libéré.

**Returns:**
booléen - `true` si le flux doit être libéré ; sinon, `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Obtient le conteneur de flux.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Utilisez avec précaution. Vous devrez libérer le conteneur de flux après récupération.
