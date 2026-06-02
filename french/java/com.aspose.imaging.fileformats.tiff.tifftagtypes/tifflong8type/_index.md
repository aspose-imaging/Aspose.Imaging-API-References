---
title: "TiffLong8Type"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type Tiff non signé 64 bits."
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

Le type Tiff non signé 64 bits.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | Initialise une nouvelle instance de la classe [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type). |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | Initialise une nouvelle instance de la classe [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValues()](#getValues--) | Obtient les valeurs. |
| [setValues(long[] value)](#setValues-long---) | Définit les valeurs. |
| [getValuesContainer()](#getValuesContainer--) | Obtient le conteneur de valeurs. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getValue()](#getValue--) | Obtient la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Définit la valeur que ce type de données contient. |
| [getElementSize()](#getElementSize--) | Obtient la taille de l'élément. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


Initialise une nouvelle instance de la classe [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


Initialise une nouvelle instance de la classe [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |
| valeurs | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Obtient les valeurs.

Valeur: les valeurs de l'étiquette.

**Returns:**
long[] - les valeurs.
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


Définit les valeurs.

Valeur: les valeurs de l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | les valeurs. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Obtient le conteneur de valeurs.

**Returns:**
com.aspose.ms.System.Array - le conteneur de valeurs.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtient le type de la balise.

Valeur: le type d'étiquette.

**Returns:**
int - le type d'étiquette.
### getValue() {#getValue--}
```
public Object getValue()
```


Obtient la valeur que ce type de données contient.

**Returns:**
java.lang.Object - la valeur que ce type de données contient.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Définit la valeur que ce type de données contient.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | la valeur que ce type de données contient. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtient la taille de l'élément.

**Returns:**
byte - taille de l'élément.
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
