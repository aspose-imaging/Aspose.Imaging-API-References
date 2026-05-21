---
title: "TiffDataType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type de données TIFF."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Le type de données TIFF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getElementSize()](#getElementSize--) | Obtient la taille de l'élément en octets. |
| [getDataSize()](#getDataSize--) | Obtient la taille de la valeur de la balise. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments. |
| [getId()](#getId--) | Obtient l'identifiant de la balise sous forme de nombre. |
| [getTagId()](#getTagId--) | Obtient l'identifiant de la balise. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | Obtient la taille des données alignée sur une frontière de 4 octets (int) ou de 8 octets (long). |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Obtient la taille supplémentaire de la valeur de la balise en octets (dans le cas où la balise ne peut pas contenir la valeur complète). |
| [getValue()](#getValue--) | Obtient la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Définit la valeur que ce type de données contient. |
| [isValid()](#isValid--) | Obtient une valeur indiquant si les données de l'étiquette sont valides. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Lit les données de l'étiquette. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | Effectue un clonage profond de cette instance. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Écrit les données de l'étiquette. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
| [toString()](#toString--) | Renvoie une `System.String` qui représente cette instance. |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtient la taille de l'élément en octets.

**Returns:**
byte - la taille de l'élément en octets.
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


Obtient la taille de la valeur de la balise.

**Returns:**
long - la taille de la valeur de l'étiquette.
### getCount() {#getCount--}
```
public abstract long getCount()
```


Obtient le nombre d'éléments.

Valeur : le nombre d'éléments.

**Returns:**
long - le nombre d'éléments.
### getId() {#getId--}
```
public final int getId()
```


Obtient l'identifiant de la balise sous forme de nombre.

**Returns:**
int - identifiant de l'étiquette en tant que nombre.
### getTagId() {#getTagId--}
```
public int getTagId()
```


Obtient l'identifiant de la balise.

**Returns:**
int - L'identifiant de l'étiquette.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Obtient le type de la balise.

**Returns:**
int - Le type d'étiquette.
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


Obtient la taille des données alignée sur une frontière de 4 octets (int) ou de 8 octets (long).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sizeOfTagValue | byte | Taille de la valeur de l'étiquette. |

**Returns:**
long - la taille des données alignées en octets.
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Obtient la taille supplémentaire de la valeur de la balise en octets (dans le cas où la balise ne peut pas contenir la valeur complète).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sizeOfTagValue | byte | Taille de la valeur de l'étiquette : 4 ou 8 pour BigTiff. |

**Returns:**
long - la taille des données supplémentaires en octets.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtient la valeur que ce type de données contient.

**Returns:**
java.lang.Object - La valeur.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Définit la valeur que ce type de données contient.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | La valeur. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Obtient une valeur indiquant si les données de l'étiquette sont valides. L'étiquette valide contient des données qui peuvent être conservées. L'étiquette invalide ne peut pas être stockée.

**Returns:**
boolean - `true` si les données de l'étiquette sont valides ; sinon, `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Lit les données de l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Le flux de données. |
| position | long | La position de l'étiquette. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Un objet à comparer avec cette instance. |

**Returns:**
int - Un entier signé de 32 bits qui indique l'ordre relatif des objets comparés. La valeur de retour a les significations suivantes : Valeur Signification Inférieure à zéro Cette instance est inférieure à `obj`. Zéro Cette instance est égale à `obj`. Supérieure à zéro Cette instance est supérieure à `obj`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Effectue un clonage profond de cette instance.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Écrit les données de l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Le flux de données. |
| additionalDataOffset | long | Le décalage où écrire les données supplémentaires. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Écrit les données d'étiquette supplémentaires.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Le flux de données. |

**Returns:**
long - Le nombre réel d'octets écrits.
### toString() {#toString--}
```
public String toString()
```


Renvoie une `System.String` qui représente cette instance.

**Returns:**
java.lang.String - Une `System.String` qui représente cette instance.
