---
title: "TiffUndefinedType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type tiff non défini."
type: docs
weight: 26
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public class TiffUndefinedType extends TiffDataType
```

Le type tiff non défini.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffUndefinedType(int tagId)](#TiffUndefinedType-int-) | Initialise une nouvelle instance de la classe `TiffUndefinedType`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getData()](#getData--) | Obtient ou définit les données. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit les données. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getValue()](#getValue--) | Obtient ou définit la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtient ou définit la valeur que ce type de données contient. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffUndefinedType(int tagId) {#TiffUndefinedType-int-}
```
public TiffUndefinedType(int tagId)
```


Initialise une nouvelle instance de la classe `TiffUndefinedType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### getData() {#getData--}
```
public byte[] getData()
```


Obtient ou définit les données.

Valeur : les données.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtient ou définit les données.

Valeur : les données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getCount() {#getCount--}
```
public long getCount()
```


Obtient le nombre d'éléments.

Valeur : le nombre d'éléments.

**Returns:**
long
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtient le type de la balise.

Valeur: le type d'étiquette.

**Returns:**
int
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
