---
title: "TiffSLong8Type"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type Tiff non signé 64 bits."
type: docs
weight: 21
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffSLong8Type extends TiffCommonArrayType
```

Le type Tiff non signé 64 bits.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffSLong8Type(int tagId)](#TiffSLong8Type-int-) | Initialise une nouvelle instance de la classe [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValues()](#getValues--) | Obtient les valeurs. |
| [setValues(long[] values)](#setValues-long---) | Définit les valeurs. |
| [getValuesContainer()](#getValuesContainer--) | Obtient le conteneur de valeurs. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getValue()](#getValue--) | Obtient la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtient la valeur que ce type de données contient. |
| [getElementSize()](#getElementSize--) | Obtient la taille de l'élément. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffSLong8Type(int tagId) {#TiffSLong8Type-int-}
```
public TiffSLong8Type(int tagId)
```


Initialise une nouvelle instance de la classe [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Obtient les valeurs.

Valeur: les valeurs de l'étiquette.

**Returns:**
long[] - les valeurs.
### setValues(long[] values) {#setValues-long---}
```
public void setValues(long[] values)
```


Définit les valeurs.

Valeur: les valeurs de l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeurs | long[] | Les valeurs. |

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


Obtient la valeur que ce type de données contient.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | La valeur que ce type de données contient. |

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
