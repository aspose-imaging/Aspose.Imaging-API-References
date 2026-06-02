---
title: "TiffUnknownType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type tiff inconnu."
type: docs
weight: 27
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

Le type tiff inconnu. Dans le cas où le tag tiff ne peut pas être reconnu, ce type est instancié.

Notez que le `TiffUnknownType` n'est pas sérialisé de nouveau dans le flux.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | Initialise une nouvelle instance de la classe `TiffUnknownType`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient le nombre d'éléments. |
| [getOffsetOrValue()](#getOffsetOrValue--) | Obtient la valeur de décalage pour des données supplémentaires ou la valeur elle-même dans le cas où le compteur est 1. |
| [getStream()](#getStream--) | Obtient le flux à partir duquel lire les données supplémentaires. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Obtient la taille supplémentaire de la valeur de la balise en octets (dans le cas où la balise ne peut pas contenir la valeur complète). |
| [getValue()](#getValue--) | Obtient ou définit la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtient ou définit la valeur que ce type de données contient. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
| [toString()](#toString--) | Renvoie une `System.String` qui représente cette instance. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


Initialise une nouvelle instance de la classe `TiffUnknownType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Le flux à lire. |
| tagType | int | Type du tag. |
| tagId | int | L'identifiant du tag. |
| count | long | La valeur du compteur. |
| offsetOrValue | long | Le décalage ou la valeur. |

### getCount() {#getCount--}
```
public long getCount()
```


Obtient le nombre d'éléments.

Valeur : le nombre d'éléments.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


Obtient la valeur de décalage pour des données supplémentaires ou la valeur elle-même dans le cas où le compteur est 1.

Valeur : le décalage ou la valeur.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


Obtient le flux à partir duquel lire les données supplémentaires.

Valeur : le flux à partir duquel lire les données.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtient le type de la balise.

Valeur: le type d'étiquette.

**Returns:**
int
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
public Object getValue()
```


Obtient ou définit la valeur que ce type de données contient.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Obtient ou définit la valeur que ce type de données contient.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
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
