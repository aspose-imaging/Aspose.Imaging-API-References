---
title: "TiffLongType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type long tiff."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflongtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffLongType extends TiffCommonArrayType
```

Le type long tiff.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffLongType(int tagId)](#TiffLongType-int-) | Initialise une nouvelle instance de la classe `TiffLongType`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValues()](#getValues--) | Obtient ou définit les valeurs. |
| [setValues(long[] value)](#setValues-long---) | Obtient ou définit les valeurs. |
| [getValuesContainer()](#getValuesContainer--) | Obtient le conteneur de valeurs. |
| [getElementSize()](#getElementSize--) | Obtient la taille de l'élément en octets. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getValue()](#getValue--) | Obtient ou définit la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtient ou définit la valeur que ce type de données contient. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffLongType(int tagId) {#TiffLongType-int-}
```
public TiffLongType(int tagId)
```


Initialise une nouvelle instance de la classe `TiffLongType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### getValues() {#getValues--}
```
public long[] getValues()
```


Obtient ou définit les valeurs.

Valeur: les valeurs.

**Returns:**
long[]
### setValues(long[] value) {#setValues-long---}
```
public void setValues(long[] value)
```


Obtient ou définit les valeurs.

Valeur: les valeurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Obtient le conteneur de valeurs.

Valeur : le conteneur de valeurs.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtient la taille de l'élément en octets.

Valeur : la taille de l'élément en octets.

**Returns:**
byte
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
