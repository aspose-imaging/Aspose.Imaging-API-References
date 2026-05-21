---
title: "StreamContainer"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente un conteneur de flux qui contient le flux et fournit des routines de traitement du flux."
type: docs
weight: 109
url: /fr/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Représente un conteneur de flux qui contient le flux et fournit des routines de traitement du flux.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Initialise une nouvelle instance de la classe `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | Initialise une nouvelle instance de la classe `StreamContainer`. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Initialise une nouvelle instance de la classe `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | Initialise une nouvelle instance de la classe `StreamContainer`. |
## Champs

| Champ | Description |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Spécifie le nombre d'octets de lecture et d'écriture lors de la lecture séquentielle. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | Effectue une conversion explicite de `com.aspose.imaging.StreamContainer` vers `System.IO.Stream`. |
| [getSyncRoot()](#getSyncRoot--) | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |
| [getPosition()](#getPosition--) | Obtient ou définit la position actuelle dans le flux. |
| [setPosition(long value)](#setPosition-long-) | Obtient ou définit la position actuelle dans le flux. |
| [getStream()](#getStream--) | Obtient le flux de données. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Obtient une valeur indiquant si ce flux est libéré à la fermeture. |
| [getLength()](#getLength--) | Obtient ou définit la longueur du flux en octets. |
| [setLength(long value)](#setLength-long-) | Obtient ou définit la longueur du flux en octets. |
| [canRead()](#canRead--) | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| [canSeek()](#canSeek--) | Obtient une valeur indiquant si le flux prend en charge le repositionnement. |
| [canWrite()](#canWrite--) | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| [flush()](#flush--) | Efface tous les tampons de ce flux et provoque l'écriture de toutes les données tamponnées sur le dispositif sous-jacent. |
| [write(byte[] bytes)](#write-byte---) | Écrit tous les octets spécifiés dans le flux. |
| [writeByte(byte value)](#writeByte-byte-) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet. |
| [read(byte[] bytes)](#read-byte---) | Lit des octets pour remplir le tampon d'octets spécifié. |
| [toBytes()](#toBytes--) | Convertit les données du flux en tableau `byte`. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Convertit les données du flux en tableau `byte`. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus. |
| [readByte()](#readByte--) | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte. |
| [seek(long offset, int origin)](#seek-long-int-) | Définit la position dans le flux actuel. |
| [seekBegin()](#seekBegin--) | Définit la position du flux au début du flux. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Enregistre (copie) toutes les données du flux vers le flux spécifié. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(String filePath)](#save-java.lang.String-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | Copie les données contenues vers un autre `StreamContainer`. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | Copie les données contenues vers un autre `StreamContainer`. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Initialise une nouvelle instance de la classe `StreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


Initialise une nouvelle instance de la classe `StreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | com.aspose.ms.System.IO.Stream | Le flux. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Initialise une nouvelle instance de la classe `StreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux de données. |
| disposeStream | boolean | si défini sur `true` le flux sera libéré lorsque le conteneur sera libéré. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


Initialise une nouvelle instance de la classe `StreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | com.aspose.ms.System.IO.Stream | Le flux de données. |
| disposeStream | boolean | si défini sur `true` le flux sera libéré lorsque le conteneur sera libéré. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Spécifie le nombre d'octets de lecture et d'écriture lors de la lecture séquentielle.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Effectue une conversion explicite de `com.aspose.imaging.StreamContainer` vers `System.IO.Stream`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |

**Returns:**
com.aspose.ms.System.IO.Stream - Le résultat de la conversion.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée.

Valeur : L'objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer.

Valeur : La position actuelle du flux.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer.

Valeur : La position actuelle du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


Obtient le flux de données.

Valeur : Le flux de données.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Obtient une valeur indiquant si ce flux est libéré à la fermeture.

Valeur : `true` si le flux est libéré à la fermeture ; sinon, `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à Stream\#getLength().getLength() de la position de départ du flux passée au constructeur de StreamContainer.

Valeur : La longueur du flux.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à Stream\#getLength().getLength() de la position de départ du flux passée au constructeur de StreamContainer.

Valeur : La longueur du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


Obtient une valeur indiquant si le flux prend en charge la lecture.

Valeur : `true` si le flux prend en charge la lecture ; sinon, `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Obtient une valeur indiquant si le flux prend en charge le repositionnement.

Valeur : `true` si le flux prend en charge le déplacement ; sinon, `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Obtient une valeur indiquant si le flux prend en charge l'écriture.

Valeur : `true` si le flux prend en charge l'écriture ; sinon, `false`.

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Efface tous les tampons de ce flux et provoque l'écriture de toutes les données tamponnées sur le dispositif sous-jacent.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Écrit tous les octets spécifiés dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| octets | byte[] | Les octets à écrire. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | L'octet à écrire dans le flux. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Lit des octets pour remplir le tampon d'octets spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| octets | byte[] | Les octets à remplir. |

**Returns:**
int - Le nombre d'octets lus. Cette valeur peut être inférieure au nombre d'octets dans le tampon s'il n'y a pas assez d'octets dans le flux.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Convertit les données du flux en tableau `byte`.

**Returns:**
byte[] - Les données du flux converties en tableau `byte`.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Convertit les données du flux en tableau `byte`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à partir de laquelle commencer la lecture des octets. |
| bytesCount | long | Le nombre d'octets à lire. |

**Returns:**
byte[] - Les données du flux converties en tableau `byte`.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Un tableau d'octets. Lorsque cette méthode retourne, le tampon contient le tableau d'octets spécifié avec les valeurs entre `offset` et (`offset` + `count` - 1) remplacées par les octets lus depuis la source actuelle. |
| offset | int | Le décalage d'octet basé sur zéro dans `buffer` à partir duquel commencer à stocker les données lues depuis le flux actuel. |
| count | int | Le nombre maximal d'octets à lire depuis le flux actuel. |

**Returns:**
int - Le nombre total d'octets lus dans le tampon. Cela peut être inférieur au nombre d'octets demandés si autant d'octets ne sont pas disponibles actuellement, ou zéro (0) si la fin du flux a été atteinte.
### readByte() {#readByte--}
```
public int readByte()
```


Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte.

**Returns:**
int - L'octet non signé converti en Int32, ou -1 si la fin du flux est atteinte.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Définit la position dans le flux actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| offset | long | Un décalage d'octet relatif au paramètre `origin`. Cette valeur représente le décalage depuis la position de départ du flux passée au constructeur de StreamContainer. |
| origin | int | Une valeur de type `System.IO.SeekOrigin` indiquant le point de référence utilisé pour obtenir la nouvelle position. |

**Returns:**
long - La nouvelle position dans le flux actuel.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Définit la position du flux au début du flux. Cette valeur représente le décalage depuis la position de départ du flux passée au constructeur de StreamContainer.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Un tableau d'octets. Cette méthode copie `count` octets de `buffer` vers le flux actuel. |
| offset | int | Le décalage d'octet basé sur zéro dans `buffer` à partir duquel commencer à copier les octets vers le flux actuel. |
| count | int | Le nombre d'octets à écrire dans le flux actuel. |

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut `ReadWriteBytesCount` et la valeur du flux `Length`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Le flux vers lequel enregistrer les données. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux `Length`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Le flux vers lequel enregistrer les données. |
| bufferSize | int | Le tampon. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Le flux vers lequel enregistrer les données. |
| bufferSize | int | La taille du tampon. Par défaut, la valeur `ReadWriteBytesCount` est utilisée. |
| length | long | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur `Length`. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut `ReadWriteBytesCount` et la valeur du flux `Length`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données du flux. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux `Length`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données du flux. |
| bufferSize | int | La taille du tampon. Par défaut, la valeur `ReadWriteBytesCount` est utilisée. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données du flux. |
| bufferSize | int | La taille du tampon. Par défaut, la valeur `ReadWriteBytesCount` est utilisée. |
| length | long | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur `Length`. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Copie les données contenues vers un autre `StreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux vers lequel copier. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Copie les données contenues vers un autre `StreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux vers lequel copier. |
| length | long | Le nombre d'octets à écrire. |

