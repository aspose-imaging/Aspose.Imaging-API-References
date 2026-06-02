---
title: "SplitStreamContainer"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente un conteneur de flux fractionné qui contient le flux et fournit des routines de traitement du flux."
type: docs
weight: 108
url: /fr/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Représente un conteneur de flux fractionné qui contient le flux et fournit des routines de traitement du flux.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Initialise une nouvelle instance de la classe `SplitStreamContainer`. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Initialise une nouvelle instance de la classe `SplitStreamContainer`. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | Initialise une nouvelle instance de la classe `SplitStreamContainer`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |
| [getPosition()](#getPosition--) | Obtient la position actuelle dans le flux. |
| [setPosition(long value)](#setPosition-long-) | Définit la position actuelle dans le flux. |
| [getLength()](#getLength--) | Obtient la longueur du flux en octets. |
| [setLength(long value)](#setLength-long-) | Définit la longueur du flux en octets. |
| [canRead()](#canRead--) | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| [canSeek()](#canSeek--) | Obtient une valeur indiquant si le flux prend en charge le repositionnement. |
| [canWrite()](#canWrite--) | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | Insère le conteneur de flux à la position spécifiée. |
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
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Initialise une nouvelle instance de la classe `SplitStreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Initialise une nouvelle instance de la classe `SplitStreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux de données. |
| disposeStream | boolean | si défini sur `true` le flux sera libéré lorsque le conteneur sera libéré. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Initialise une nouvelle instance de la classe `SplitStreamContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |
| disposeStream | boolean | si défini sur `true` libère le flux. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée.

**Returns:**
java.lang.Object - L'objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée.
### getPosition() {#getPosition--}
```
public long getPosition()
```


Obtient la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer.

**Returns:**
long - La position actuelle du flux.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La position actuelle du flux. |

### getLength() {#getLength--}
```
public long getLength()
```


Obtient la longueur du flux en octets. Cette valeur est inférieure à `System.IO.Stream.Length` de la position de départ du flux passée au constructeur de StreamContainer.

**Returns:**
long - La longueur du flux.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Définit la longueur du flux en octets. Cette valeur est inférieure à `System.IO.Stream.Length` de la position de départ du flux passée au constructeur de StreamContainer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La longueur du flux. |

### canRead() {#canRead--}
```
public boolean canRead()
```


Obtient une valeur indiquant si le flux prend en charge la lecture.

**Returns:**
boolean - `true` si le flux prend en charge la lecture ; sinon, `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Obtient une valeur indiquant si le flux prend en charge le repositionnement.

**Returns:**
boolean - `true` si le flux prend en charge le déplacement ; sinon, `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Obtient une valeur indiquant si le flux prend en charge l'écriture.

**Returns:**
boolean - `true` si le flux prend en charge l'écriture ; sinon, `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


Insère le conteneur de flux à la position spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | int | La position où insérer. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux à insérer. |
| disposeStream | boolean | si défini sur `true` libère le flux. |

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

