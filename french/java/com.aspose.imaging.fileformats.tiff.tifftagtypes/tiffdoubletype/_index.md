---
title: "TiffDoubleType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type double tiff."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

Le type double tiff.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | Initialise une nouvelle instance de la classe `TiffDoubleType`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValues()](#getValues--) | Obtient les valeurs. |
| [setValues(double[] value)](#setValues-double---) | Définit les valeurs. |
| [getValuesContainer()](#getValuesContainer--) | Obtient le conteneur de valeurs. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getElementSize()](#getElementSize--) | Obtient la taille de l'élément en octets. |
| [getValue()](#getValue--) | Obtient la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Définit la valeur que ce type de données contient. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


Initialise une nouvelle instance de la classe `TiffDoubleType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### getValues() {#getValues--}
```
public double[] getValues()
```


Obtient les valeurs.

**Returns:**
double[] - Les valeurs.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


Définit les valeurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] | Les valeurs. |

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
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtient la taille de l'élément en octets.

**Returns:**
byte - La taille de l'élément en octets.
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
