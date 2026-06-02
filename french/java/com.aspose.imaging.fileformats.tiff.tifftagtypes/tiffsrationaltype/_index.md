---
title: "TiffSRationalType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type rationnel signé tiff."
type: docs
weight: 23
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffSRationalType extends TiffCommonArrayType
```

Le type rationnel signé tiff.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffSRationalType(int tagId)](#TiffSRationalType-int-) | Initialise une nouvelle instance de la classe `TiffSRationalType`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValues()](#getValues--) | Obtient ou définit les valeurs. |
| [setValues(TiffSRational[] value)](#setValues-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Obtient ou définit les valeurs. |
| [getValuesContainer()](#getValuesContainer--) | Obtient le conteneur de valeurs. |
| [getElementSize()](#getElementSize--) | Obtient la taille de l'élément en octets. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getValue()](#getValue--) | Obtient ou définit la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtient ou définit la valeur que ce type de données contient. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffSRationalType(int tagId) {#TiffSRationalType-int-}
```
public TiffSRationalType(int tagId)
```


Initialise une nouvelle instance de la classe `TiffSRationalType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### getValues() {#getValues--}
```
public TiffSRational[] getValues()
```


Obtient ou définit les valeurs.

Valeur: les valeurs.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[]
### setValues(TiffSRational[] value) {#setValues-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void setValues(TiffSRational[] value)
```


Obtient ou définit les valeurs.

Valeur: les valeurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

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
