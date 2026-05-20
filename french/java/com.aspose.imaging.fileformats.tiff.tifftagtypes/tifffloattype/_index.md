---
title: "TiffFloatType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type flottant tiff."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffFloatType extends TiffCommonArrayType
```

Le type flottant tiff.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffFloatType(int tagId)](#TiffFloatType-int-) | Initialise une nouvelle instance de la classe `TiffFloatType`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValues()](#getValues--) | Obtient les valeurs. |
| [setValues(float[] value)](#setValues-float---) | Définit les valeurs. |
| [getElementSize()](#getElementSize--) | Obtient la taille de l'élément en octets. |
| [getValuesContainer()](#getValuesContainer--) | Obtient le conteneur de valeurs. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getValue()](#getValue--) | Obtient la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Définit la valeur que ce type de données contient. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffFloatType(int tagId) {#TiffFloatType-int-}
```
public TiffFloatType(int tagId)
```


Initialise une nouvelle instance de la classe `TiffFloatType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### getValues() {#getValues--}
```
public float[] getValues()
```


Obtient les valeurs.

**Returns:**
float[] - Les valeurs.
### setValues(float[] value) {#setValues-float---}
```
public void setValues(float[] value)
```


Définit les valeurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Les valeurs. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtient la taille de l'élément en octets.

**Returns:**
byte - La taille de l'élément en octets.
### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Obtient le conteneur de valeurs.

**Returns:**
com.aspose.ms.System.Array - Le conteneur de valeurs.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtient le type de la balise.

**Returns:**
int - Le type d'étiquette.
### getValue() {#getValue--}
```
public Object getValue()
```


Obtient la valeur que ce type de données contient.

**Returns:**
java.lang.Object - La valeur.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Définit la valeur que ce type de données contient.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | La valeur. |

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
